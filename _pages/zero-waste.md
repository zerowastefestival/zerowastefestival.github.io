---
layout: page
permalink: /zero-waste/
title: "Zero Waste"
---

If you want to find out more about the Zero Waste lifestyle and how to live a low impact life, then you're absolutely right here. Below you can find a map of Zero Waste stores around Ireland. Check out our articles below to learn more.

{% include zw-map.html %}

<h2 itemprop="name">Articles</h2>
<div class="tiles">
{% for post in site.categories.zero-waste %}
	{% include zw-grid.html %}
{% endfor %}
</div>

 
