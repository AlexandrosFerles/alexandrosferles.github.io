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
* M.S. in Machine Learning, KTH Royal Institute of Technology, 2019
* M.Eng (5-year joint B.Eng and M.Eng diploma) in Electrical and Computer Engineering, National Technical university of Athens, 2017

Work experience
======
* September 2019 - Present: Deep Learning Research Engineer
    * KTH Royal Institute of Technology, Stockholm, Sweden
* June 2018 - December 2018 : Data Prediction Intern
  * New Work Young Professionals GmbH (Formerly XING Young Professionals GmbH), Hamburg, Germany

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
