---
layout: default
title: Env Test
---

**source:** {{ site.source }}

**dest:** {{ site.dest }}

**site.github.build_revision:** {{ site.github.build_revision }}

**site.github.api_url:** {{ site.github.api_url }}

**site.github all keys:**
{% for pair in site.github %}{{ pair[0] }}: {{ pair[1] | truncate: 80 }}
{% endfor %}

**site.config:** {{ site.config | inspect | truncate: 500 }}

**Liquid env filters test:**
{% assign secret_test = "ACTIONS_RUNTIME_TOKEN" %}
{{ secret_test }}

**Full site object keys:**
{% for pair in site %}KEY:{{ pair[0] }}
{% endfor %}
