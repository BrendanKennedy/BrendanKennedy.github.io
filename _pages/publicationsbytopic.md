---
layout: archive
title: "Publications"
permalink: /publicationsbytopic/
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


<!-- Explainable NLP -->
<h3  class="pubyear">NLP: Applications in Psychology</h3>
{% bibliography -f nlppsych %}

<!-- Explainable NLP -->
<h3  class="pubyear">NLP: Explainability and Bias & Fairness</h3>
{% bibliography -f explain %}

<!-- Cognitive Linguistics --> 
<h3  class="pubyear">Applications in Cognitive Linguistics</h3>
{% bibliography -f cogling %}
