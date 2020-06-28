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
* B.S. in Computer Science with Honors, Gonzaga University, 2016
* Ph.D in Computer Science, University of Southern California, 2022 (expected)

Research Interests 
======
* Computer Science
  * Natural Language Processing
  * f
  * Supervisor: Professor Hub

Publications
======
<h3  class="pubyear">Preprints and In-Progress</h3>
{% bibliography -f preprints %}

{% for y in page.years %}
  <h3  id="{{y}}" class="pubyear">{{y}}</h3>
  {% bibliography -f published -q @*[year={{y}}]* %}
{% endfor %}

Work experience
======
* Fall 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Dr. Andrew Goodney
  
Skills
======
* Programming
  * Python
    * Data Science libraries: sklearn, pandas, numpy, matplotlib, gensim
    * Deep learning libraries: tensorflow, keras
    * NLP: nltk, 
  * R
    * ggplot2
    * That's it
* Latex
* Project management with Git
* Multitasking projects
* Are these all my relevant skills? Probably not, lol
* I'm an good writer
  
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
* I review articles for journals (for free)
