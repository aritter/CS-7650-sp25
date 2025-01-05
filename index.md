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

- Location: Instructional Center 103
- Time: MW 5:00 pm - 6:15 pm
- [Piazza](https://piazza.com/gatech/spring2025/cs7650/) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/815066) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/16sXgPtwr_oPrw0XhVvBfcA-3T2fqheKUGMP457nG7DM/edit?usp=sharing)

{% for module in site.modules %}
{{ module }}
{% endfor %}
