---
layout: home
title: CS 7650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

The lectures for this course will be streamed and recorded using Bluejeans.  The link is available [here](https://bluejeans.com/764447839/0241).

- Location: Instructional Center 211
- Time: MW 2:00 pm - 3:15 pm
- [Piazza](https://piazza.com/class/kxuyn4sdh0p6ve) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/344493) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1GZHMzZ_p4APtYRTiReEJ_PU4wkdQSHgUGTd3xptCO8Q/edit?usp=sharing)

{% for module in site.modules %}
{{ module }}
{% endfor %}
