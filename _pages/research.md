---
layout: single
title: "Research"
permalink: /research/
author_profile: true
header:
  teaser: /assets/images/onkk.hn.bk.2.png
---

My main research focuses on better understanding air pollution, 
from emissions through atmospheric physico-chemical transformations to exposure and effects on human health.
I am also interested in studying the interactions between air pollution, climate and the biosphere. 

##### Research grants/projects

06. [**WellHome**](https://gtr.ukri.org/projects?ref=NE%2FW002116%2F1#/tabOverview):West London Healthy Home and Environment Study, NERC £2.9m, 2021-2025. *Role:* ***Research co-PI***
05. [**APeX**](https://gtr.ukri.org/project/6D2FF57F-BE97-4070-B074-685CC802D05F): An Air Pollution Exposure model to integrate protection of vulnerable groups into the UK Clean Air Programme, NERC £1.4m, 2019-2022. *Role: Researcher*
04. [**CLUE**](https://gtr.ukri.org/projects?ref=MR%2FR00322X%2F1):Cognitive DeveLopment in the Urban Environment, MRC £618k, 2018-2021 . *Role: Researcher*
03. [**SOA**](https://gtr.ukri.org/projects?ref=NE%2FS006699%2F1&pn=0&fetchSize=10&selectedSortableField=date&selectedSortOrder=ASC#/tabOverview): Quantitative attribution of secondary organic aerosol in Beijing to its precursors, NERC £319k, 2019-2021. *Role:* ***Case of Support writer and Researcher***
02. [**APHH-AIRPOLL**](https://gtr.ukri.org/projects?ref=NE%2FN007190%2F1): Sources and emissions of air pollutants in Beijing, NERC £1.4m, 2016-2020. *Role: Researcher*
01. [**HEXACOMM**](https://cordis.europa.eu/project/id/315760/reporting): Human exposure to aerosol contaminants in modern microenvironments, H2020 £3.2, 2013-2016. *Role:* ***ECR fellowship***

##### Research topics

My research topics are: 1) Physico-chemical properties of air pollutants; 2) Source apportionment of aerosols; 3) Human exposure and health impacts of air pollution; 4) Air quality policy. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
