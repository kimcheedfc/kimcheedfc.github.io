---
layout: archive
title: "Articles"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "A summary of all the things happening in the church."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
