---
layout: default
title: Env Test
---

**source path:** {{ site.source }}

**github.repository:** {{ site.github.repository_name }}

**github.owner:** {{ site.github.owner_name }}

**github.url:** {{ site.github.url }}

**github.environment:** {{ site.github.environment }}

**github.hostname:** {{ site.github.hostname }}

**github.pages_hostname:** {{ site.github.pages_hostname }}

**github.private:** {{ site.github.private }}

**github.releases_url:** {{ site.github.releases_url }}

**Full github object:** {{ site.github | inspect | truncate: 2000 }}
