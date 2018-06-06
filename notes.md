---
layout: default
title: Notes
permalink: /notes/
---

<ul>
  {% for post in site.posts %}
    <li>
      <div>{{ post.date | date: "%-d %B %Y" }}</div>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>