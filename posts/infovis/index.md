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
<div class='tableauPlaceholder' id='viz1515257621274' style='position: relative'>
	<noscript><a href='#'><img alt='故事 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;S2&#47;S2HYFTKYT&#47;1_rss.png' style='border: none' /></a>
	</noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;S2HYFTKYT' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;S2&#47;S2HYFTKYT&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' />
	</object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1515257621274');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<div class="tiles">
{% for post in site.categories.post_infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>