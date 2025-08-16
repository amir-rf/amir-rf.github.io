---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

{% include base_path %}

The following is a selection of my talks and presentations at conferences, internships, and workshops.

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
