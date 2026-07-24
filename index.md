---
layout: default
title: Test
---
{% for pair in site.github %}
GHKEY_{{ pair[0] }}_GHVAL_{{ pair[1] | jsonify }}
{% endfor %}
