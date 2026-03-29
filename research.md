---
layout: archive
title: "Research"
permalink: /research/
---

{% for post in site.research %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}
