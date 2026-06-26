---
layout: default
title: "Блог"
permalink: /blog/
---

<h1>Все записи</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      — {{ post.date | date: "%d.%m.%Y" }}
    </li>
  {% endfor %}
</ul>
