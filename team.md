---
layout: archive
title: "Team"
permalink: /hpc_resource_management/team/
---

{% for member in site.team %}
  <h2><a href="{{ member.url | relative_url }}">{{ member.title }}</a></h2>
  <p>{{ member.role }}</p>
{% endfor %}
