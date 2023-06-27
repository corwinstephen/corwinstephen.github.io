---
layout: page
title: Textures
---
{% for image in site.static_files %}
{% if image.path contains 'img/textures' %}
![texture]({{site.url}}{{ image.path }})
{% endif %}
{% endfor %}