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
* Ph.D. in University of Electronic Science and Technology of China, 2026 (expected)
* B.S. in University of Electronic Science and Technology of China, 2021

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Competitions
======
  <ul>{% for post in site.competitions reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>