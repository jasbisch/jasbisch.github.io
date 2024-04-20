---
layout: archive
title: "Conference contributions"
permalink: /contributions/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.contributions reversed %}
  {% include archive-single-contribution.html %}
{% endfor %}
