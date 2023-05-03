---
# layout: home
layout: single
title: Posts
permalink: /posts/
author_profile: true
---

# Some writing I did

<ul>
  {% for post in site.posts %}
    <!-- <li> -->
      {% include archive-single.html type=entries_layout %}
      <!-- <a href="{{ post.url }}">{{ post.title }}</a> -->
      <!-- {{ post.excerpt}} -->
    <!-- </li> -->
  {% endfor %}
</ul>