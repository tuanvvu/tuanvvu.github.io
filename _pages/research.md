---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  teaser: /assets/images/onkk.hn.bk.2.png
---

My research has focused on better understanding air pollution, 
from emissions through atmospheric chemical and physical transformations to exposure and effects on human health & climate change. 
Toward that end, I have carried out many sampling campaigns of air pollution (mainly aerosols) in UK, Spain, 
Italy, Czech, South Korea and currently in China and India.

Selected research projects:
01.NERC grant, “An Air Pollution Exposure model to integrate protection of vulnerable groups into the UK Clean Air Programme” (role: key researcher): £1.4m, 2019-22
02.NERC grant, “Quantitative attribution of secondary organic aerosol in Beijing to its precursors” (role: proposal writer & key researcher): £273k, 2019-21
03.NERC grant, “Sources and emissions of air pollutants in Beijing” (key researcher): £1.4m, 2016-20
04.H2020-EU grant, “Human exposure to aerosol contaminants in modern microenvironments” (ECR fellowship): £413k, 2013-16

My publication list can be found on the Google Scholar website

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
