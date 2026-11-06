---
layout: page
title: "Office Hours / Instructors"
nav_order: 6
description: A listing of all the course staff members.
---

## Spring 2027 instructor

**Ty Ferre** (he/him). Office hours, contact details, and teaching-assistant assignments will be announced.

## Staff from the 2026 offering

The profiles below identify the staff associated with the retained 2026 materials. They are not Spring 2027 staffing assignments.

### Instructor (2026)

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching assistants (2026)

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
