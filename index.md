---
layout: front
---

{% include projects/listing.html %}

{% comment %}
// example: only show projects within given categories:
{% include projects/listing.html categories="kitchen furniture" %}
// example: also filter out low ranked projects:
{% include projects/listing.html categories="webpage graphics" exclude_priority=4 %}
// example: only show projects with given tags:
{% include projects/listing.html tags="aluminium wood cnc" %}
// example: only show projects in given list (filters like above can be added):
{% include projects/listing.html projects=my_array  %}
{% endcomment %}
