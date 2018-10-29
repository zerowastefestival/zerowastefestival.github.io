---
layout: page
permalink: /news/
title: News
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %}
    
	{% else if %}
	  {% include post-grid.html %}
	{% endif %}
{% endfor %}
</div>
