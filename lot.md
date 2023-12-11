---
layout: page
title: An empty lot
---
{% for image in site.static_files %}
{% if image.path contains 'img/lot' %}
![{{image.modified_time}}]({{site.url}}{{ image.path }})
{% endif %}
{% endfor %}