---
layout: home
permalink: students
title: "Current Students"
excerpt: ""
image:
  feature: 20150613_074.jpg
---

<h2 class="post-title">PhD Candidates</h2>
<div class="tiles">
{% for post in site.categories.phd-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div><h2 class="post-title">Masters and Honours students</h2></div>
<div class="tiles">
{% for post in site.categories.masters-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
