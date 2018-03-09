---
layout: default
title: Notes
permalink: /notes/
---

<nav>
  <ul>
    <li class="nav__item {% if location == '/' or page.layout == 'default' %}active {% endif %}"><a href="/">back home</a></li>
  </ul>
</nav>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>