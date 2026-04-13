---
layout: archive
title: "Research"
permalink: /research/
---

<h3>Debug: Found {{ site.research | size }} research items</h3>

<ul>
{% for item in site.research %}
  <li>{{ item.title }} - top_level: {{ item.top_level }} - path: {{ item.path }}</li>
{% endfor %}
</ul>

<hr>

{% for item in site.research %}
  {% if item.top_level and item.title %}
    <h2>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
    </h2>
  {% endif %}
{% endfor %}