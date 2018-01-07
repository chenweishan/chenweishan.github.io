---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature:
  teaser:
---

在此展示作品——关于信息可视化作品
![image](https://note.youdao.com/yws/public/resource/be4e6934f7cdbeba3b59c4639f1bebde/xmlnote/3E4A1D472C584BDF9A883D72C73546AB/1620)


<div class="tiles">
{% for post in site.categories.infovis%}
  {% include post-grid.html %}
{% endfor %}