---
layout: archive
title: "作品集"
date: 2017-12-20
modified:
excerpt: "信息可视化小试牛刀"
tags: []
image: 
  feature: design.jpg 
  teaser: design.jpg
---

在此展示关于作品集——关于信息可视化和网页设计的作品

<div class="tiles">
{% for post in site.categories.sample %}
  {% include post-grid.html %}
{% endfor %}