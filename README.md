---
layout: default
title: Materials
permalink: /
---

{% for p in site.pages %}
{% if p.title and p.title <> "Materials" and p.exclude_front_page <> "yes" %}
## [{{ p.title }}]({{ site.baseurl }}{{ p.url }})
{% endif %}
{% endfor %}
