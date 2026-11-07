---
layout: page
title: Schedule
nav_order: 2
description: Spring 2027 course schedule.
---

## Spring 2027 schedule

Classes meet Monday, Wednesday, and Friday, 2:00 to 2:50 pm, Arizona time (MST, UTC−7). The first week, January 13 and 15, is reserved for the field trip, so classroom meetings begin January 20 after the January 18 university holiday. Spring break has no classes on March 8, 10, or 12.

The dates below follow the [University of Arizona academic calendar](https://studentaffairs.arizona.edu/important-dates). Reading Day is May 6, with no classes. The final exam is Friday, May 7, 1:00 to 3:00 pm MST, following the [official Spring 2027 final-exam schedule](https://registrar.arizona.edu/faculty-staff-resources/room-course-scheduling/schedule-classes/final-exams/final-exams-spring-2027).

Topic timing, homework assignment and due dates, and the oral midterm date are tentative and may be adjusted by Ty Ferré. Homework deadlines shown below are at 10:00 pm MST.

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
