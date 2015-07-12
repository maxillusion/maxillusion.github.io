---
layout: portfolio
permalink: /portfolio/
title: "Derniers projets"
---

<div class="tiles">
{% for post in site.categories['portfolio'] %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->