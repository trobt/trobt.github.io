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
* Ph.D student (2025.07 - Current)

Work experience
======
* Summer 2024: Research Assistant
  * Location
  * Duties included: Porgramming
  * Supervisor: Professor XXX
  
Skills
======
* Skill 1 - Coding
  * Sub-skill 2.1 - CV
  * Sub-skill 2.2 - Control
  * Sub-skill 2.3 - DL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
