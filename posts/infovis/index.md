---
layout: archive
title: "信息可视化笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: Information_visualization_reading_notes.gif
  teaser:
---

在此展示网页设计和信息可视化的读书笔记


<div class="tiles">
{% for post in site.categories.post_infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>