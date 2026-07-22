---
layout: default
title: LineageOS builds by A2L5E0X1
---

# LineageOS builds by A2L5E0X1
  
## Available devices

{% assign sorted_pages = site.pages | sort: 'title' %}

{% for page in sorted_pages %}
{% if page.title and page.url and page.url contains "/devices/" %}
- [{{ page.title }} ({{ page.codename }})]({{ page.url | relative_url }})
{% endif %}
{% endfor %}
