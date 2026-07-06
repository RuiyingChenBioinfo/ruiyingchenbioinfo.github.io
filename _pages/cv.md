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
* Ph.D in Genomics, University of Chinese Academy of Sciences (Beijing, China), 2021-now
* B.S. in Bioinformatics, Huazhong Agricultural University (Wuhan, China), 2017-2021

Skills
======
* single-cell and spatial multi-omics analysis
  * Gene expression gradient analysis
  * Trajectory analysis
  * Gene regulatory network analysis
  * Co-expression analysis
  * Spatial cell-cell communication analysis

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
