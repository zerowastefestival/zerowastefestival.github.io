---
layout: archive
permalink: /news/
title: News

comments: false
ads: false
share: false
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %}
    // do nothing
	{% else if %}
	  {% include post-grid.html %}
	{% endif %}
{% endfor %}
</div>
