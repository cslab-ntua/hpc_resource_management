---
layout: archive
title: "Research"
permalink: /research/
---

{% for item in site.research %}
  {% if item.top_level and item.title %}
    <h2>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </h2>
  {% endif %}
{% endfor %}
