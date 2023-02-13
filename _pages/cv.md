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
* B.S. in Petroleum Engineering, 2009
* M.S. in Petroleum Engineering, 2014
* M.S. in Applied Mathematics , 2020
* Ph.D in ... (Actively looking for Ph.D position in Mathematics or Computer Science)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Numerical Simulation and Modeling 
* Computational fluid dynamics (CFD)
* Data analytics
  * Machine learning and Deep learning 
  * Data analysis and Exploration
  * Econometrics
* Optimization and Control theory 

Publications
======
  <ul>{% [for post in site.publications](https://scholar.google.com/citations?hl=en&user=xXjexJkAAAAJ&view_op=list_works&sortby=pubdate) %}
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
