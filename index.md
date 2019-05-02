---
layout: page
permalink: /
---

# Zero Waste Festival Ireland

We are planning to bring our next Zero Waste Festival to Dublin in the summer. Stay tuned for more updates. In the mean time, you can check out our ongoing series of [Pop-up Events](/pop-up) in Dublin.

For all the latest updates head over to the [News](/news) section and follow our social media accounts on [Facebook](https://www.facebook.com/ZeroWasteFestivalIreland) and [Instagram](https://www.instagram.com/zerowastefestirl), and [Twitter](https://twitter.com/ZeroWasteFest). You can also subscribe to our [Atom feed]({{ site.baseurl}}/feed.xml).


# Latest News

For all news check the [News](/news) section.

<div class="tiles">
{% for post in site.posts  limit:8 %}
  {% if post.category == "team" or post.category == "event" or post.category == "events" or post.category == "zero-waste" %} 
  
  {% else if %}
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

