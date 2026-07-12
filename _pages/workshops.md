---
layout: single
title: "Workshops"
permalink: /workshops/
author_profile: true
---

{% for workshop in site.workshops %}

### [{{ workshop.title }}]({{ workshop.url | relative_url }})

{{ workshop.excerpt }}

{% endfor %}
