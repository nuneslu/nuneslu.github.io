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
* Ph.D in 3D Representation Learning and Semantic Scene Understanding, University of Bonn, 2026 (expected)
* M.S. in Computer Science, University of São Paulo, 2020
* B.S. in Computer Science, University of São Paulo, 2018

Work experience
======
* Apr/2020 - Nov/2020: Software Engineer
  * IVEX
  * Duties includes: Development of front and back-end for a safety assessment tool and urban simulated environments in the context of autonomous vehicles.

* Jan/2019 - Apr/2020: Technical Leader
  * Juristec+
  * Duties included: Coordination of a web crawler programming team for data collection, and development/maintenance of a back-end database server.

* Jan/2018 - Aug/2018: Python Developer
  * Juristec+
  * Duties included: Development of web crawler Python scripts for data collection.
  
Skills
======
* Languages:
  * Portuguese: Native
  * English: Advanced
  * German: Beginner
* Programming:
  * C
  * Python
  * Java
  * R
  * Matlab
* Technical experience
  * Unix-based operating system
  * Robot Operating System (ROS)
  * Parallel programming
  * SQL/NoSQL Database

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
