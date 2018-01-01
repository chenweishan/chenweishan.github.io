---
layout: archive
title: "作品集"
date: 2017-12-1T10:36:45-16:25
modified:
tags: ["https://segmentfault.com/q/1010000005851755/a-1020000005852001"]
image: 
  feature: design.jpg
  teaser: design.jpg
---

在此展示作品——关于网页设计和信息可视化作品
<div class="page-header">
    <h1>博客</h1>
</div>

<ul class="posts">
    {% for post in site.categories.blog %}
    <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<div class="tiles">
{% for post in site.categories.sample %}
  {% include post-grid.html %}
{% endfor %}