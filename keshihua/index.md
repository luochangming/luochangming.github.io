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
<p>概要
以欢乐世界，海底公园，主题公园，旋转木马为keywords。通过对比全国欢乐世界分布发现，数据结果遵循了人口分布规律，欢乐世界主要集中在人口密布的城市地区；通过树形图统计分析，江苏为游乐设施聚集最多的省份，同时，游乐设施场所并非按照城市经济发达程度排序，故游乐设施场所分布与城市经济发达程度关系不大。
</p>
<meta name="viewport" content="width=device-width">
<link rel="stylesheet" href="css/styles.css">
<div class='tableau1' style='width:1300; height:600;'> 
<iframe src="https://public.tableau.com/profile/.31354527#!/vizhome/_18170/1_1" width="1300" height="600"></iframe> 
</div>
 
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
