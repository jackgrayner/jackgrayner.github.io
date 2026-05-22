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
* PhD in Biology, University of St Andrews, 2020 (expected)
* Master's by research (MRes) in Ecology, University of Nottingham, 2016
* BSc Hons in Evolutionary Biology, University of Exeter, 2014

Work experience
======
* 2023-Present: Postdoc Researcher
  * University of Maryland
  * Wilkinson Lab

* 2020-2023: Postdoc Researcher
  * University of St Andrews
  * Bailey Lab

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
  
