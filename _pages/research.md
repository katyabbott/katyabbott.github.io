---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## **Under construction**


## Coastal processes in the North Indian Ocean
![image](https://raw.githubusercontent.com/katyabbott/katyabbott.github.io/refs/heads/master/images/jgrc26218-fig-0008-m.jpg)

## Submesoscale biophysical interactions
![image](https://raw.githubusercontent.com/katyabbott/katyabbott.github.io/refs/heads/master/images/subducted_chl_o2.png)

## Ventilation of oxygen-deficient zones


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
