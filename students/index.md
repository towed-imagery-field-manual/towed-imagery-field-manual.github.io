---
layout: home
permalink: students
title: "Current Students"
excerpt: ""
image:
  feature: banner6.jpg
---
<h2 class="post-title">PhD Candidates</h2>
<div class="tiles">
{% for post in site.categories.phd-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<div class="tiles">
{% for post in site.categories.masters-students %}
	{% include masters-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
