---
layout: archive
title: "Research"
permalink: /research/
---

{% for item in site.research %}
  {% if item.top_level %}
    <div class="archive__item">
      <h2 class="archive__item-title">
        <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      </h2>
    </div>
  {% endif %}
{% endfor %}
