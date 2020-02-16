---
layout: page
permalink: /
---

Wherever you are on your Zero Waste journey, meet us at one of our upcoming events to get in touch with likeminded people and learn more about the various aspects of Zero Waste living.

<!--
Our next [Zero Waste Festival](/airfield-festival-food-2019/) is at the [Festival of Food](https://www.festivaloffood.ie/) in Airfield.

<picture>
	<source 
		media="(min-width: 650px)" 
		srcset="/images/events/2019-09-festival-of-food/airfield-announcemant-wide.jpg"> 
	<img 
		src="/images/events/2019-09-festival-of-food/airfield-announcemant-narrow.jpg" 
		alt="Zero Waste Festival Airfield" 
		style="width:auto;">
</picture>
//-->

# Latest News

Find our latest announcements here of and be sure to check out the [News](/news) and [Events](/events) section to see what we've been up to in the past.

<div class="tiles">
{% for post in site.posts  limit:8 %}
  {% if post.category != "team" and post.category != "draft" %} 
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

