---
layout: archive
title: "Publications"
permalink: /publicationsbytopic/
author_profile: true
---

<aside class="sidebar__right">
            <nav class="toc">
              <header><h4 class="nav__title"><i class="fa fa-file-text"></i> On This Page</h4></header>
              <ul class="toc__menu">
  <li><a href="#">Preprints and Submitted</a></li>
  <li><a href="#">Explainable NLP</a></li>                  
  <li><a href="#">NLP Applications in Cognitive Linguistics</a></li>
</ul>
            </nav>
          </aside>

<a href="/publicationsbytopic/"><button type="button" class="btn" style="outline:none">By Topic </button></a> 
<a href="/publicationsbyyear/"><button type="button" class="btn" style="outline:none"> By Year  </button></a> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- Explainable NLP -->
<h3  class="pubyear">Explainable NLP</h3>
{% bibliography -f explain %}

<!-- Cognitive Linguistics --> 
<h3  class="pubyear">NLP Applications in Cognitive Linguistics</h3>
{% bibliography -f cogling %}