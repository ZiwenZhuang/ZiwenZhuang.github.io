---
layout: archive
title: "Projects"
type: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-talk.html %}
{% endfor %}