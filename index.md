---
layout: page
permalink: /
---

We are hosting regular pop-up Zero Waste Festivals at various locations in Ireland. Find out more about our upcoming and past events here.


# Zero Waste Festival

Join us for our next Zero Waste Festival on Sunday, December 2, at the Green Door Market in Bluebell, Dublin. 

For all the latest updates see the news section here or follow our social media accounts on [Facebook](https://www.facebook.com/ZeroWasteFestivalIreland) and [Instagram](https://www.instagram.com/zerowastefestirl), and [Twitter](https://twitter.com/ZeroWasteFest) or subscribe to our [Atom feed]({{ site.baseurl}}/feed.xml).


# News

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %}
    
	{% else if %}
	  {% include post-grid.html %}
	{% endif %}
{% endfor %}
</div>

