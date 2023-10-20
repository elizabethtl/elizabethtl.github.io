---
layout: single
title: About
permalink: /about/
author_profile: true
---

## Education

{% for edu in site.data.education %}
  <strong>{{edu.school}}</strong>, {{edu.city}} 
  <br>
  <b>{{edu.degree}}</b>, {{edu.major}}
  <br>
  <i>{{edu.start}} ~ {{edu.end}}</i>
{% endfor %}

## Experience

{% for exp in site.data.experience %}
  <strong>{{exp.job}}</strong> @ {{exp.company}}
  <br>
  {{exp.city}}
  <br>
  <i>{{exp.start}} ~ {{exp.end}}</i>
  <br>
  {{exp.desc}}
{% endfor%}
