---
layout: archive
title: "Teaching"
permalink: /courses/
author_profile: true
redirect_from:
  - /teaching
---

{% include base_path %}

Teaching
======
  <ul>{% for post in site.teaching reverse%}
    {% include archive-single-talk.html %}
  {% endfor %}</ul>
