---
layout: article
permalink: /

comments: false
ads: true
share: false 
---

![Zero-Waste-Week](/images/18-09-Festival/Zero-Waste-Week-MainHeader.png)

We are hosting regular pop-up Zero Waste Festivals at various locations in Ireland. Find out more about our upcoming and past events here.

# Zero Waste Festival

Join us for our next Zero Waste Festival in September in Dublin. For all the latest updates and news follow our social media accounts on [Facebook](https://www.facebook.com/ZeroWasteFestivalIreland) and [Instagram](https://www.instagram.com/zerowastefestirl), or subscribe to our [Atom feed]({{ site.baseurl}}/feed.xml).


# News

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %}
    
	{% else if %}
	  {% include post-grid.html %}
	{% endif %}
{% endfor %}
</div>

