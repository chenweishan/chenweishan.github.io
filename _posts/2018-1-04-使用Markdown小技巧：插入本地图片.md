---
layout: article
title:  "使用Markdown小技巧：插入本地图片"
date:   2018-1-04 20:17:50 +0800
categories: posts infovis
image:
  teaser: tableua2.jpg
  feature: 
---
使用Markdown小技巧：插入本地图片
{% include toc.html %}


## 起因
在利用jeykll制作个人博客的过程中，使用Markdown写文章再插入网页中是比较简单的操作。但是在进行这一系列操作的时候，可能会面临着“本地图片（截图）无法上传到Markdown“的问题。如果使用网络图片，那得先找一个可以上传并下载的网络服务器资源；若是使用指定绝对路径的本地图片（如E:\Documents\1.jpg），则其又违背了云笔记的逻辑，当在其他电脑上访问该笔记时，得先将图片资源放置在相同的绝对路径中。之后我找到了解决方法，希望能帮助大家~

## 第一步 新建有道云笔记
新建一个普通的有道云笔记，然后将本地图片上传到有道云笔记中，点击分享的按钮，就会自动生成一个链接，最后复制并查看分享。![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/29524BFB1E9642BC8630471273B1E2A4/1246)分享成功后，在弹出窗口中复制分享的网址。右键——复制图片链接，就可以生成图片链接
## 第二步 使用工具栏按钮
插入有道云示例图片，该操作只是为了提示读者，若并不清楚图片条目的语法，可以借助于工具栏按钮。
![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/CD29F57504114834A4C96C77790566CA/1299)

## 第三步 贴到相应地方
上述操作后，编辑区出现一行图片描述，如下：
```![image](http://note.youdao.com/favicon.ico)```</br>
该行语法结构为：</br>
```![图片提示文字](图片链接) ```
</br>本次插入的，是有道云笔记的示例图片。若我们想要插入自己的图片，只需要修改其中的链接即可。然后Markdown就会显现出图片出来，如图：
</br>![image](https://note.youdao.com/yws/public/resource/12019ccf8991d56958475054e3435db1/xmlnote/FD9449A4AD8C486A9C908D43C2364BBC/1304)

## 小提醒
- 三步骤操作就可以方便的将本地图片上传到Markdown，是不是很轻松？接下来还有一点步骤的小提醒：
- -若图片内容涉及机密，请谨慎分享噢。
- 在分享时，若提示“笔记中的纸张背景无法在分享页面展示”，可忽略此提示，选择“暂不升级”

## 参考资料
[万能的知乎](https://www.zhihu.com/)

