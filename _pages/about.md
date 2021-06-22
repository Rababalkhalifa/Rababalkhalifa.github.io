---
permalink: /
title: "CV"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Education
======
* B.S. in Computing, Girls College in Dammam, 2010
* M.S. in Advanced Computing - Machine Learning, Data Mining and High-Performance Computing, University of Bristol, 2018
* Ph.D (expected) in Longitudinal Natural Language Processing, Queen Mary University of London, 2023 

Work experience
======
* 2013 - currently : Lecturer 
  * Imam Abdulrahman bin Faisal University
  
* 2012: Lab Instructor /Administrator  
  * Prince Mohammad Bin Fahd University
  
* 2011: Programmer 
  * Electronia Ltd.
  
Skills
======
* Perseverance and motivation
* Organisation
* Communication and Teamwork

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