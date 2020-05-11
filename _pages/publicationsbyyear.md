---
layout: archive
title: "Publications"
permalink: /publicationsbyyear/
years: [2016,2018,2019,2020]
author_profile: true
---

<aside class="sidebar__right">
            <nav class="toc">
              <header><h4 class="nav__title"><i class="fa fa-file-text"></i> On This Page</h4></header>
              <ul class="toc__menu">
  <li><a href="#">Preprints and Submitted</a></li>
  <li><a href="#2020">2020</a></li>
  <li><a href="#2019">2019</a></li>
  <li><a href="#2018">2018</a></li>
  <li><a href="#2016">2016</a></li>
</ul>
            </nav>
          </aside>

<a href="/publicationsbytopic/"><button type="button" class="btn" style="outline:none">By Topic </button></a> 
<a href="/publicationsbyyear/"><button type="button" class="btn" style="outline:none"> By Year  </button></a> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for y in page.years %}
  <h3  id="{{y}}" class="pubyear">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
