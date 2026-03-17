---
layout: default
title: 投资笔记
---

# 投资笔记

<ul>
{% for post in site.categories.investment %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>