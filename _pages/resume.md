---
layout: single
title: Experiece
permalink: /experience/
author_profile: true
---

<h2> Education</h2>

{% for edu in site.data.education %}
<div style="display: flex; justify-content: space-between; font-size:85%;">
  <strong>{{edu.school}}</strong>
  {{edu.city}}
</div>
<div style="display: flex; justify-content: space-between;">
  <p><b>{{edu.degree}},</b>{{edu.major}}</p>
  <p><i>{{edu.start}} ~ {{edu.end}}</i></p>
</div>
{% endfor %}

<h2> Experience</h2>

{% for exp in site.data.experience %}
  <div style="font-size: 85%; margin: 0 0 0 1;"><strong>{{exp.job}}</strong> @ {{exp.company}}</div>
  <div style="display: flex; justify-content: space-between; font-size: 80%; margin: 0 0 0 1;">
    {{exp.city}}
    <i>{{exp.start}} ~ {{exp.end}}</i>
  </div>
  <div style="font-size: 80%;">{{exp.desc}}</div>
  <br>
{% endfor%}
