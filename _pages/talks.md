---
layout: archive
title: ''
permalink: /talks/
author_profile: true
---

善恶有名，智者不拘也。 天理有常，明者不弃也。

{% if site.talkmap_link == true %}

<p style="text-decoration: underline">
  <a href="/talkmap.html">See a map of all the places I've given a talk!</a>
</p>

{% endif %} {% for post in site.talks reversed %} {% include
archive-single-talk.html %} {% endfor %}
