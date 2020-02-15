---
layout: page
permalink: /zero-waste/
title: "Zero Waste"
---

If you want to find out more about the Zero Waste lifestyle and how to live a low impact life, then you're absolutely right here. Below you can find a map of Zero Waste stores around Ireland*. Check out our articles below to learn more.

<small>* Sorry if the map is not centered at Ireland, you can move in the map to find Ireland. We are working on solving this issue soon.</small>

 <div id="zerowastemap" style="display: block;" data-lang="" data-type="" data-center="" data-allow="fullscreen,geolocation" data-style="width: 100%; height: 500px; max-width: 100%;"></div>
 <script async src="//zerowastemap.org/zerowastemap-embed.js?x16511"></script> 

<h2 itemprop="name">Articles</h2>
<div class="tiles">
{% for post in site.categories.zero-waste %}
	{% include zw-grid.html %}
{% endfor %}
</div>
