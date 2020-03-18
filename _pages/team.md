---
layout: page
permalink: /team/
title: "Team"
---

We are a community run initiative to facilitate networking learning and sharing. We aim to bring you an ongoing series of pop-up festivals with workshops, talks, screenings, and meet-up sessions taking place on a regular basis in different locations. You can meet our lovely team of dedicated volunteers here, and if you like to get involved yourself, check out the [Get Involved](/get-involved) section.

<div class="tiles team">
{% for post in site.categories.team %}
	{% include team-grid.html %}
{% endfor %}
</div>

