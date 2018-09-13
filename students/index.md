---
layout: home
permalink: students
title: "Current Students"
excerpt: ""
image:
  feature: banner6.jpg
---
<div><h2 class="post-title">PhD Candidates</h2></div>
<div class="tiles">
{% for post in site.categories.phd-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<div><h2 class="post-title">Masters and Honours students</h2></div>
<div class="tiles">
{% for post in site.categories.masters-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
