---
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% for item in site.data.navigation.main %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}

An [XML sitemap]({{ '/sitemap.xml' | relative_url }}) is also available.
