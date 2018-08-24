---
layout: archive
permalink: /news/
title: News

comments: false
ads: true
share: false
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %}
    
	{% else if %}
	  {% include post-grid.html %}
	{% endif %}
{% endfor %}
</div>
