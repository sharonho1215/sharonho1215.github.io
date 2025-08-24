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
* MBBChir, University of Cambridge, 2026 (expected)
* MEng in Bioengineering and Information Engineering, University of Cambridge, 2023
* BA, University of Cambridge

Work experience
======

* September 2023 – present:  Developing a signal quality assessment tool for single lead ECGs 
  * Developed a tool to assess the signal quality of hand-held ECGs through using state-of-the-art QRS detection algorithms and signal processing techniques. This will contribute to automated atrial fibrillation detection
  * Supervisor: Dr Peter Charlton, Department of Public Health and Primary Care, University of Cambridge
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
