---
layout: default
category: About
title: Research Interests
description: |
---

{% assign year_secs = 31536000 %}
{% assign now_ts = "now" | date: "%s" %}
{% assign arrived_ts = "February 14, 2012" | date: "%s" %}
{% assign years_since_arriving = now_ts | minus: arrived_ts | divided_by: year_secs %}

His interests are in the area of systems software, dependability in distributed systems in the context of different applications like cloud/edge computing, mobile systems and services, Internet of Things (IoT), networking, fault-tolerance, information and communication systems (ICT), and Internet technologies.
