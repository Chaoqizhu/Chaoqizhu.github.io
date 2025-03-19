---
layout: archive
title: "📝"
permalink: /论著/
author_profile: true
---

## 论著清单详见 <a href="{{site.author.googlescholar}}">谷歌学术</a>

## 近期代表性论著

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
