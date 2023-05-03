---
# layout: home
layout: single
title: Posts
permalink: /posts/
author_profile: true
---

## Some writing I did

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>