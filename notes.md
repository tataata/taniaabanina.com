---
layout: default
title: Notes
permalink: /notes/
---

<ul class="feed">
  {% for post in site.posts %}
    <li class="feed__item">
      <small class="feed__date">{{ post.date | date: "%-d %B %Y" }}</small>
      <a href="{{ post.url }}" class="feed__link">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>