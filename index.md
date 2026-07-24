---
layout: default
title: Test
---
Site github env: {{ site.github.environment }}
Site github api url: {{ site.github.api_url }}
{% for pair in site.github %}KEY:{{ pair[0] }}{% endfor %}
