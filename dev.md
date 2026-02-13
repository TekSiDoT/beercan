---
layout: page
title: Dev
permalink: /dev/
---

Building blocks for agentic systems. Hooks, patterns, and tools I'm developing or thinking about.

{% for item in site.dev %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
