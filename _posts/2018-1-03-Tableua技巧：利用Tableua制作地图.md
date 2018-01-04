---
layout: article
title:  "Tableua技巧：利用Tableua制作地图"
date:   2018-1-03 21:33:50 +0800
categories: notes_tech posts/infovis/
image:
  teaser: photo.jpg
  feature: 
---
Tableua技巧之制作可视化精美地图
{% include toc.html %}


## 创建和填充地图!
- 想要用Tableua创建地图，首先要找好数据源，可以通过使用python或者是excel筛选整理数据。要选择有地理符号的数据，例如说是经纬度，国家省市等。便于之后制作可视化。
- 准备好数据之后，接下来就是设置地理角色，双击国家，或者是右键——地理位置，再根据你的数据设置好地理角色。如图：
![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/B210263FC1364627A39A70B9E9903145/1195)

## 形成可视化图
进行上面的操作之后，同时点击“纬度（生成）”和“经度（生成）”，右边的“智能显示”就会自动出现相适应的图表类型，点击“地图”，初步的地图就完成啦。如图：
![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/6C9A195285694BF4AABB6642B6E3D13F/1204)
## 添加标记
为了让可视化图更加的具体美观，我们可以添加一些标记。将左边“维度”的栏目中的类别拖拽到标记中，比如将keywords拖拽到“颜色”或者是“标签”的标记上。
![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/2D43B949A9FC4680B29F3A3BEB69EDC9/1209)
就会呈现出按照颜色分配的类别和详细信息。在进行一些小的设置，如边界，调整大小等，混合地图就完成了。
## 形成两个地图合并
除了上面的简单操作之外，还可以制作三维地图。
- 为了使得工作表中多一个维度，可以把“度量窗口”中的“纬度（生成）”再次拖放到行功能中，此时同时展示两个地图。
- 把“度量窗口”中的“纬度（生成）”再次拖放到行功能区中，此时同时展现了两个地图。选择双轴，两个地图重叠为一个。如图：
![image](https://pic3.zhimg.com/v2-42606585356b3b3a4249494aca08dbba_r.jpg)

## 小结
利用Tableua制作地图还是比较常见好用的，这些小技巧希望能帮助你制作美观的地图。