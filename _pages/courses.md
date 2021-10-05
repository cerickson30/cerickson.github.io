---
layout: archive
title: "Teaching"
permalink: /courses/
author_profile: true
redirect_from:
  - /teaching
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
