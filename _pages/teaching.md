---
layout: page
permalink: /teaching/
title: teaching
# description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 5
calendar: false
---

<!-- This page displays a collection of courses with detailed schedules, materials, and resources. You can organize your courses by years, terms, or topics. -->

<!-- {% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %} -->

<hr style="border: 0; border-top: 1px solid #e5e5e5; margin: 0.5rem 0 1.5rem 0;">

<div style="margin-top: 1.5rem;"></div>

## instructor

{% include courses.liquid courses=site.instructors %}

<div style="margin-top: 4.5rem;"></div>

## teaching assistant

{% include courses.liquid courses=site.teachings %}
