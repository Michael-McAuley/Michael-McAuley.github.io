---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% if site.teaching_enabled %}
  {% include base_path %}
  {% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
