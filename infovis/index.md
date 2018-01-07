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
<div class='tableauPlaceholder' id='viz1515318650295' style='position: relative'>
	<noscript><a href='#'><img alt='故事 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;1_&#47;1_5271&#47;2&#47;1_rss.png' style='border: none' /></a>
	</noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='1_5271&#47;2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;1_&#47;1_5271&#47;2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' />
	</object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1515318650295');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


<div class="tiles">
{% for post in site.categories.infovis%}
  {% include post-grid.html %}
{% endfor %}