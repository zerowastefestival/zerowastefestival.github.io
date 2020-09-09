---
layout: page
permalink: /events/
title: "Events"
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "festival" or post.category == "pop-up" or post.category == "events" %} 
	{% include grid-events.html %}
  {% endif %}
{% endfor %}
</div>


