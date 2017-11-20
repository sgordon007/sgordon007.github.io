---
layout: page
title: Publications
---

{% for pub in site.publications reversed %}
  {% if pub.authors contains "Sean Gordon" %}
  {{ pub.content }}
  {% endif %}
{% endfor %}
