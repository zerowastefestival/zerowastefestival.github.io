---
layout: page
permalink: /news/
title: News
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category != "team" and post.category != "draft" %} 
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>
