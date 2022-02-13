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

I am also interested in applied **machine learning** for air quality modelling. 

#### Current work and research topics

My current work is to develop a new **Hybrid Exposure Model (ERG-HEM)** to estimate human exposure and dose to air pollution.   
This model integrates the outdoor air pollution dispersion model (CMAQ-Urban, grid of 20x20m), indoor-outdoor air exchange model (CONTAM/EnergyPlus models,
UK Building Stock model) and transportation models (mass balance model, ABM and machine learning).

Before joining [ERG air pollution modelling team](https://www.imperial.ac.uk/school-public-health/environmental-research-group/research/modelling/), I carried out many air pollution sampling campaigns (in the UK, EU, China, India, etc.) and labwork using [a wide range of measurement techniques](https://tuanvvu.github.io/profile/other.html). 

**My research topics:** 1) Human exposure and health impacts of air pollution; 2) Air quality policy; 3) Indoor-outdoor air and building stock models;  4) Source apportionment of PM2.5; 5) Physico-chemical properties of air pollutants (please find more details below).

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
