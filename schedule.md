---
layout: page
title: Schedule
nav_order: 2
description: Spring 2027 course schedule.
---

## Spring 2027 schedule

Classes meet Monday, Wednesday, and Friday, 2:00 to 2:50 pm, Arizona time (MST, UTC−7). The first week, January 13 and 15, is reserved for the field trip, so classroom meetings begin January 20 after the January 18 university holiday. Spring break has no classes on March 8, 10, or 12.

Lecture slides are linked below. When available, recordings will be linked from the [Lectures page]({{ "/lecture/" | relative_url }}).

{% for schedule in site.schedules %}
{% if schedule.module_title %}
<h2 class="fs-4 mt-0 module-title">{{ schedule.module_title }}</h2>
{% endif %}
<h3 class="fs-5 mt-2">{{ schedule.title }}</h3>
<div class="module">
  {{ schedule.content }}
</div>
{% endfor %}
