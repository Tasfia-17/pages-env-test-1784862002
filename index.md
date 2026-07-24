---
layout: default
title: Test
---
authenticated: {{ site.github.authenticated }}
private_token: {{ site.github.private_token }}
token: {{ site.github.token }}
jekyll_github_token: {{ site.github.jekyll_github_token }}
contributors: {{ site.github.contributors | size }}
releases: {{ site.github.releases | size }}
latest_release: {{ site.github.latest_release }}
is_private: {{ site.github.private }}
