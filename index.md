---
layout: home
title: CS 4650
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

Although this is an in-person course, we plan to stream lectures using Zoom.  The link is available [here](https://gatech.zoom.us/j/93717817219?pwd=Vlpnc0Q5WVlQVUU1ZEJsLzltWnY1Zz09).

- Location: Klaus Advanced Computing 2443
- Time: MW 5:00 pm - 6:15 pm
- [Piazza](https://piazza.com/class/l6sbo1myboz2ww) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/417826) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1G2Jy78e4QH9-B_oCaQROFlVbTGiF41DgDNEyI4IEv14/edit?usp=sharing)

{% for module in site.modules %}
{{ module }}
{% endfor %}
