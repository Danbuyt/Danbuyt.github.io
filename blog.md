---
layout: default
title: "Блог"
permalink: /blog/
---

<h1>Все записи</h1>
<div class="journal-list">
  {% for post in site.posts %}
    <div class="item">
      <a href="{{ post.url }}">{{ post.title }}</a>
      — {{ post.date | date: "%d.%m.%Y" }}
    </div>
  {% endfor %}
</div>
