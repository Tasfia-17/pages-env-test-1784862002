---
layout: default
title: Test
---
config_nil: {{ site.config }}
data_keys: {{ site.data | size }}
static_files: {{ site.static_files | size }}
pages_count: {{ site.pages | size }}
jekyll_version: {{ jekyll.version }}
ruby_version: {{ site.github.versions.ruby }}
jekyll_ver: {{ site.github.versions.jekyll }}
github_pages_ver: {{ site.github.versions.github_pages }}
