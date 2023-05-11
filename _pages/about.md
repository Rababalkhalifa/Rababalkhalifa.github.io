---
permalink: /
title: "Highlights"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<!-- News
====== -->
Join us in coordinating a collaborative effort to conduct a comprehensive evaluation of text classifiers through a temporal lens, in our shared task "Longitudinal Evaluation of Model Performance" shared task. [See more info at (<a href="https://clef-longeval.github.io/">https://clef-longeval.github.io/</a>)]

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