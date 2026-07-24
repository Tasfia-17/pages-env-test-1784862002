---
layout: default
title: Env Test
---

**Jekyll version:** {{ jekyll.version }}

**site.github keys:** {{ site.github | inspect | truncate: 200 }}

**ENV via site.config:** {{ site.config | inspect | truncate: 300 }}

**site.data:** {{ site.data | inspect | truncate: 200 }}

**site.collections:** {{ site.collections | map: "label" | join: ", " }}

**Working dir path:** {{ site.source }}

**Dest dir:** {{ site.dest }}

