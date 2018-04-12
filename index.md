---
layout: archive
permalink: /
title: "Home"
content: "Hi this is the content for my page"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<picture>
  <source media="(min-width: 650px)" srcset="
https://github.com/derekponce/site/blob/gh-pages/images/Pier_DerekEthan.jpg">
  <source media="(min-width: 465px)" srcset="
https://github.com/derekponce/site/blob/gh-pages/images/Pier_DerekEthan.jpg">
  <img src="Pier_DerekEthan.jpg" alt="Pier" style="width:auto;">
</picture>


https://github.com/derekponce/site/blob/gh-pages/images/Pier_DerekEthan.jpg
