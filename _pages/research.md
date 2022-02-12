---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  teaser: /assets/images/onkk.hn.bk.2.png
---

<font size=4> My main research focuses on better understanding air pollution, 
from emissions through atmospheric physico-chemical transformations to exposure and effects on human health.
I am also interested in studying the interactions between air pollution, climate and the biosphere. </font> 

##### Research grants/projects

06. [<font size=4> West London Healthy Home and Environment Study, NERC £2.9m, 2021-2025 </font>](https://gtr.ukri.org/projects?ref=NE%2FW002116%2F1#/tabOverview). *<font size=4>Role: </font>* ***<font size=4>Research co-PI</font>***
05. [<font size=4> An Air Pollution Exposure model to integrate protection of vulnerable groups into the UK Clean Air Programme, NERC £1.4m, 2019-2022 </font>](https://gtr.ukri.org/project/6D2FF57F-BE97-4070-B074-685CC802D05F).<font size=4> *Role: Researcher*</font> 
04. [<font size=4>Cognitive DeveLopment in the Urban Environment, MRC £618k, 2018-2021 </font>](https://gtr.ukri.org/projects?ref=MR%2FR00322X%2F1). *<font size=4>Role: Researcher</font>*
03. [<font size=4> Quantitative attribution of secondary organic aerosol in Beijing to its precursors, NERC £319k, 2019-2021</font>](https://gtr.ukri.org/projects?ref=NE%2FS006699%2F1&pn=0&fetchSize=10&selectedSortableField=date&selectedSortOrder=ASC#/tabOverview). *<font size=4>Role: </font>* ***<font size=4>Case of Support writer and Researcher</font>***
02. [<font size=4> Sources and emissions of air pollutants in Beijing, NERC £1.4m, 2016-2020</font>](https://gtr.ukri.org/projects?ref=NE%2FN007190%2F1). *<font size=4>Role: Researcher</font>*
01. [<font size=4>Human exposure to aerosol contaminants in modern microenvironments, H2020 £3.2, 2013-2016/font>](https://cordis.europa.eu/project/id/315760/reporting). *<font size=4>Role: </font>* ***<font size=4>ECR fellowship</font>***

### Research topics

<font size=4>Main main research topics: 1) Physico-chemical properties of air pollutants; 2) Source apportionment of aerosols; 3) Human exposure and health impacts of air pollution; 4) Air quality policy</font>. 



<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
