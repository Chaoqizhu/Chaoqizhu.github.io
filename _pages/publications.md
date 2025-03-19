---
layout: archive
title: "论著"
permalink: /论著/
author_profile: true
---
## 著作
* 贾永刚，朱超祁，等著，内孤立波对南海北部陆坡影响研究，科学出版社，2025年
* 彭建兵，贾永刚，朱超祁，等著，琼东南盆地海底地质灾害与风险防控研究，科学出版社，2025年

## 论文清单详见 <a href="{{site.author.googlescholar}}">谷歌学术</a>
近期代表性论文
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
