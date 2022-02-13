---
layout: single
classes: wide
title: "Research Interest"
permalink: /research/
author_profile: true
header:
  teaser: /assets/images/onkk.hn.bk.2.png
---


My main research focuses on better understanding **air pollution**, 
from *emissions* through *atmospheric physico-chemical transformations* and *interactions between air pollution, climate and the biosphere* to *exposure and effects on human health*.

I am also interested in applied **machine learning and AI** for air quality modelling. 

##### Research topics

My research topics are: 1) Physico-chemical properties of air pollutants; 2) Source apportionment of aerosols; 3) Human exposure and health impacts of air pollution; 4) Air quality policy. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
