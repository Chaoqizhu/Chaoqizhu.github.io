---
layout: archive
title: "📝 Publications"
permalink: /publications/
author_profile: true
---

## Full list of papers on my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>

## Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
