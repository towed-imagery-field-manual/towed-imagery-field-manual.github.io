---
layout: home
permalink: phd-students
title: "PhD Candidates"
excerpt: ""
image:
  feature: banner6.jpg
---
<div class="tiles">
  <h2 class="post-title">PhD Candidates</h2>
{% for post in site.categories.phd-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
