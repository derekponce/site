---
layout: archive
permalink: /
title: "Home"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

Hi this is the content for my page

<picture>
  <source media="(min-width: 650px)" srcset="
https://derekponce.github.io/site/images/Pier_DerekEthan.JPG">
  <source media="(min-width: 465px)" srcset="
https://derekponce.github.io/site/images/Pier_DerekEthan.JPG">
  <img src="https://derekponce.github.io/site/images/Pier_DerekEthan.JPG" alt="Pier" style="width:auto;">
</picture>

Ignore below this

<figure class="half">
	<img src="https://derekponce.github.io/site/images/Fragrance_MostComplimented.JPG">
	<img src="https://derekponce.github.io/site/images/Fragrance_Winter.jpg">
	<figcaption>Some of my more popular fragrances. </figcaption>
</figure>
