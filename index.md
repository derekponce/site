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

<figure class="third">
	<img src="https://derekponce.github.io/site/images/Pier_DerekEthan.jpg">
	<img src="https://derekponce.github.io/site/images/Derek_Sushi.jpg">
	<img src="https://derekponce.github.io/site/images/Family_DerekMo.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>




Ignore below this

Hi this is the content for my page
<figure>
	<img src="https://derekponce.github.io/site/images/Pier_DerekEthan.jpg">
	<figcaption>Blank</figcaption>
</figure>

<picture>
  <source media="(min-width: 650px)" srcset="
https://derekponce.github.io/site/images/Pier_DerekEthan.jpg">
  <source media="(min-width: 465px)" srcset="
https://derekponce.github.io/site/images/Pier_DerekEthan.jpg">
  <img src="https://derekponce.github.io/site/images/Pier_DerekEthan.jpg" alt="Pier" style="width:auto;">
</picture>
