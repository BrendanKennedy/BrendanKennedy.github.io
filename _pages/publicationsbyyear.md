---
layout: archive
title: "Publications"
permalink: /publicationsbyyear/
years: [2020,2019,2018,2016,2015]
author_profile: true
---
<p>
* Indicates equal contribution.
</p> 
<a href="/publicationsbytopic/"><button type="button" class="btn" style="outline:none">By Topic </button></a> 
<a href="/publicationsbyyear/"><button type="button" class="btn" style="outline:none"> By Year  </button></a> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


<!-- Preprints -->
<h3  class="pubyear">Preprints and In-Progress</h3>
{% bibliography -f preprints %}

{% for y in page.years %}
  <h3  id="{{y}}" class="pubyear">{{y}}</h3>
  {% bibliography -f published -q @*[year={{y}}]* %}
{% endfor %}
