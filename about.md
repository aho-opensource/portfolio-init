---
title: About
---

{% assign image = "https://www.creativefabrica.com/wp-content/uploads/2023/05/01/Moomin-Little-My-Graphic-Graphics-68564846-1.jpg" %}
{% capture content %}
A little designer with big dreams :sparkles:

Determined but curious, fearless but friendly.
{% endcapture %}

{% include author.html name=site.author.name image=image content=content %}


Hi, I am **{{ site.author.name }}** :wave:

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
