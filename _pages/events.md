---
layout: page
permalink: /events/
title: "Events"
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "festival" or post.category == "pop-up" %} 
	{% include grid-events.html %}
  {% endif %}
{% endfor %}
</div>


