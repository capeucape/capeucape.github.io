---
layout: archive
permalink: /
title: "这是小白的新家"
---
我的愿望是你可以多来逛逛！

<div class="tiles">
	{% include sidebar-search.html %}
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}

</div><!-- /.tiles -->
