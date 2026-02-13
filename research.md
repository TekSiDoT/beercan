---
layout: page
title: Research
permalink: /research/
---

Original experiments and papers.

{% for item in site.research %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

{% if site.research.size == 0 %}
*First paper coming soon: "The Space Between Reading and Experiencing" — a study on serial vs. batch reading in AI systems.*
{% endif %}
