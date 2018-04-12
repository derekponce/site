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

