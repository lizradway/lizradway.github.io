---
layout: archive
title: "Recent"
permalink: /recent/
author_profile: true
---

{% include base_path %}

{% for post in site.recent reversed %}
  {% include archive-single.html %}
{% endfor %}
