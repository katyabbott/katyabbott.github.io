---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## **Under construction**
My research interests include remote sensing and carbon cycling in different terrestrial and marine environments. I'm especially interested in exploring interactions between physics and biogeochemistry.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
