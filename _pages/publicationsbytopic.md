---
layout: archive
title: "Publications"
permalink: /publicationsbytopic/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- Explainable NLP -->
<h3  class="pubyear">Explainable NLP</h3>
{% bibliography -f explain %}

<!-- Cognitive Linguistics --> 
<h3  class="pubyear"></h3>
{% bibliography -f cogling %}