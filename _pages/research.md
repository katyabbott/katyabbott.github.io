---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### Disentangling drivers and signals of coastal upwelling
<img src="https://raw.githubusercontent.com/katyabbott/katyabbott.github.io/refs/heads/master/images/jgrc26218-fig-0008-m.jpg" width="600" />


Coastal upwelling is canonically depicted as a quasi-steady state process in which dense, cold water is brought to the surface, supplying nutrients from the deep ocean and cooling the sea surface. In my work, I am interested in studying systems that deviate from these assumptions and understanding the implications for primary production and offshore transport. One good example of this is the Bay of Bengal coastal upwelling system, which is predominantly salinity-stratified near the surface — so upwelled water is saltier but not necessarily colder. Conclusions are mixed about whether the strong alongshore winds linked to the summer monsoon actually drive upwelling, because the coastal SST signature is not significantly different from the rest of the Bay.  In a <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024JC022023" target="_blank">recent paper</a>, we contrast the Bay of Bengal against a more typical upwelling system in the nearby Arabian Sea. Using both process-study models and observations, we show that the weak satellite SST signal in the Bay of Bengal can be explained physically by a combination of intraseasonal wind variability and vertical density stratification, but also by patchy satellite data that aliases the strongest upwelling events. These results demonstrate biases in traditional methods used to investigate coastal upwelling. I am currently working to generalize these results to other regions and characterize the effects on offshore transport. 


### Submesoscale biophysical interactions
<img src="https://raw.githubusercontent.com/katyabbott/katyabbott.github.io/refs/heads/master/images/subducted_chl_o2.png" width="600" />

### Ventilation of oxygen-deficient zones


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
