---
layout: page
permalink: /news/
title: News
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" or post.category == "event" or post.category == "events" or post.category == "zero-waste" %} 
  
  {% else if %}
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>
