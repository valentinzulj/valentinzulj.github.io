---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Statistics, Uppsala University, 2025 (expected).
* M.A. in Statistics, Uppsala University, 2020.
* B.A. in Statistics, Lund University, 2018.

  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* PhD representative to the board of the Department of Statistics, Uppsala University (2024-25).
