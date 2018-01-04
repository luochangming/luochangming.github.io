---
layout: archive
title:  "高德地图信息可视化作品"
date:   2017-11-30 22:07:50 +0800
modified:
excerpt: "游乐设施场所分布与城市经济发达程度是否有关"
tags: []
image:
  feature: Tower_of_Babel.jpg
  teaser: Tower_of_Babel.jpg
---
meta charset="utf-8">
<meta name="viewport" content="width=device-width">
<link rel="stylesheet" href="css/styles.css">
<div class='tableau1' style='width:1350; height:600;'> 
<iframe src="https://public.tableau.com/profile/.31354527#!/vizhome/_18170/1_1" width="1350" height="600"></iframe> 
</div>
 
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
