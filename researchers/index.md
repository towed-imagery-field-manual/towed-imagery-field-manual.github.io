---
layout: home
permalink: researchers
title: "Researchers and Staff"
excerpt: ""
image:
  feature: banner4.jpg
---
<h2 class="post-title">Researchers</h2>
<div class="tiles">
{% for post in site.categories.researchers %}
	{% include post-grid.html %}
{% endfor %}
{% for post in site.categories.staff %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div><h2 class="post-title">Staff</h2></div>
<div class="tiles">
{% for post in site.categories.staff %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
