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
* B.S. in Information Security, Shanghai Jiao Tong University, 2020
* Ph.D in Optimization, University of Oxford, 2024 (expected)

Work experience
======
* Summer 2020: Research Assistant at Shanghai Jiao Tong University University
  * Research topic: multi-robot virtual-physical interaction system
  * Supervisor: Professor Jianping He
  
Skills
======
* C++
* ROS
* MATLAB
* MYSQL

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
