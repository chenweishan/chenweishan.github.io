---
layout: archive
title: "读书笔记"
date: 2017-12-1T10:36:45-16:25
modified:
tags: []
image: 
  feature: years.jpg
  teaser: years.jpg
---

在此展示网页设计和信息可视化的读书笔记
{% highlight html linenos %}
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
		<p>这是一个小的尝试</p>
    </head>
    <body>
    </body>
</html>
{% endhighlight %}

<div class="tiles">
{% for post in site.categories.note %}
  {% include post-grid.html %}
{% endfor %}