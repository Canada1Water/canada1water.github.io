---
layout: page
title: Modules
description: Course modules and learning materials.
nav_order: 3
has_children: true
---

# Course Modules

This course is organized into 10 comprehensive modules, each designed to build your expertise in data management for HydroGeoSphere modeling.

{% for module in site.modules %}
{{ module }}
{% endfor %}
