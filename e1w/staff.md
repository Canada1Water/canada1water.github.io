---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 5
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign team_members = site.staffers | where: 'role', 'Team Member' %}
{% assign num_team_members = team_members | size %}
{% if num_team_members != 0 %}
## Team Members

{% for staffer in team_members %}
{{ staffer }}
{% endfor %}
{% endif %}
