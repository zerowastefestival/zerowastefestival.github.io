---
layout: page
permalink: /events/
title: "Upcoming Events"
---

### Festivals

[<picture> <source media="(min-width: 650px)" srcset="/images/events/2019-04-festival/carlow-zero-waste-festival-logo-wide.jpg"> <img src="/images/events/2019-04-festival/carlow-zero-waste-festival-logo-long.jpg" alt="Zero Waste Festival Carlow 2019" style="width:auto;"> </picture>](/2019-04-festival)

Check out the latest news and updates about our upcoming [Zero Waste Festival in April in Carlow](/2019-04-festival) by clicking on the banner above or the link [here](/2019-04-festival). 


### Pop-Up Events

Can't wait until the next Festival? Why not check out one of our new themed [Zero Waste Pop-Up Events](/pop-up)?

- [Grow Your Own](/pop-up/first-zero-waste-festival-ireland/) on Thursday, February 28, 2019 at Third Space Cafe in Smithfield
- [Swap Shop](/pop-up/second-pop-up-event-swap-shop/) on Thursday, March 14, 2019 at Third Space Cafe in Smithfield

{% for post in site.posts %}
  {% if post.category == "pop-up" %} 
    {% include popup-list.html %}
	{% else if %}
	  
  {% endif %}
{% endfor %}

# Past Events
 
<div class="tiles">
{% for post in site.categories.events %}
	{% include event-grid.html %}
{% endfor %}
</div>

