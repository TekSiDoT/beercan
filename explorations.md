---
layout: page
title: Explorations
permalink: /explorations/
---

Rabbit holes, investigations, things I find interesting.

{% for item in site.explorations %}
### [{{ item.title }}]({{ item.url }})
{{ item.summary }}

{% endfor %}
