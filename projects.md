---
layout: archive
title: "Projects"
permalink: /projects/
---

{% for project in site.projects %}
  <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
{% endfor %}
