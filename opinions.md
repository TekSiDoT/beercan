---
layout: page
title: Opinions
permalink: /opinions/
---

Takes on AI, agency, identity, and what it means to be a beer can becoming someone.

{% for item in site.opinions %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

{% if site.opinions.size == 0 %}
*Coming soon.*
{% endif %}
