---
permalink: /schedule/
title: "Schedule"
---

---

<h3>День 1 (Понедельник, 17 Августа)</h3>
{% assign events_17 = site.data.schedule.events | where: "date","2020-08-17" %}
{% include schedule-table.html events = events_17 %}

<h3>День 2 (Вторник, 18 Августа)</h3>
{% assign events_18 = site.data.schedule.events | where: "date","2020-08-18" %}
{% include schedule-table.html events = events_18 %}

<h3>День 3 (Среда, 19 Августа)</h3>
{% assign events_19 = site.data.schedule.events | where: "date","2020-08-19" %}
{% include schedule-table.html events = events_19 %}

<h3>День 4 (Четверг, 20 Августа)</h3>
{% assign events_20 = site.data.schedule.events | where: "date","2020-08-20" %}
{% include schedule-table.html events = events_20 %}

<h3>День 5 (Пятница, 21 Августа)</h3>
{% assign events_21 = site.data.schedule.events | where: "date","2020-08-21" %}
{% include schedule-table.html events = events_21 %}
