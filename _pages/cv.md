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
* M.S. in Software and Network Engineering, University of Duisburg-Essen, 2022 (with distinction)
* M.S. in Technomathematics, University of Duisburg-Essen, 2021 (with distinction)
* B.S. in Technomathematics, University of Duisburg-Essen, 2018 (with distinction)

Work experience
======
* Since 2022: Research and Teaching Assistant
  * University of Duisburg-Essen
  * Course of Study: Computer Science
  * Supervisor: Professor Dr. Barbara König
  
Language Skills
======
* German: Native
* English: Level C2
* French: Level B1

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
  
<!--
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
