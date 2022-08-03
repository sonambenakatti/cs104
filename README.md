---
layout: home
title: Home
nav_exclude: true
permalink: index.html
seo:
  type: Course
  name: CS 104
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->


Course Materials
{% for module in site.modules %} {{ module }} {% endfor %}
