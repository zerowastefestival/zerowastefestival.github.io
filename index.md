---
layout: page
permalink: /
---

We are hosting regular pop-up Zero Waste Festivals at various locations in Ireland. Find out more about our upcoming and past events here.


# Zero Waste Festival

Join us for our next Zero Waste Festival in April in Carlow. Stay tuned for more updates.

[<picture> <source media="(min-width: 650px)" srcset="/images/events/2019-02-festival/carlow-zero-waste-festival-logo-wide.jpg"> <img src="/images/events/2019-02-festival/carlow-zero-waste-festival-logo-long.jpg" alt="Zero Waste Festival Carlow" style="width:auto;"> </picture>](/2019-02-festival)

For all the latest updates see the [News](/news) section here or follow our social media accounts on [Facebook](https://www.facebook.com/ZeroWasteFestivalIreland) and [Instagram](https://www.instagram.com/zerowastefestirl), and [Twitter](https://twitter.com/ZeroWasteFest) or subscribe to our [Atom feed]({{ site.baseurl}}/feed.xml).


# Latest News

For all news check the [News](/news) section.

<div class="tiles">
{% for post in site.posts  limit:9 %}
  {% if post.category == "team" or post.category == "event" or post.category == "events" or post.category == "zero-waste" %} 
  
  {% else if %}
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

