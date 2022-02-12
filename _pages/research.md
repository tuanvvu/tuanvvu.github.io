---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  teaser: /assets/images/onkk.hn.bk.2.png
---

My main research focuses on better understanding air pollution, 
from emissions through atmospheric physico-chemical transformations to exposure and effects on human health.
I am also interested in studying the interactions between air pollution, climate and the biosphere.

### Research grants/projects

[West London Healthy Home and Environment Study, NERC £2.9m, 2021-2025](https://gtr.ukri.org/projects?ref=NE%2FW002116%2F1#/tabOverview). ***Role: Research co-PI***

[An Air Pollution Exposure model to integrate protection of vulnerable groups into the UK Clean Air Programme, NERC £1.4m, 2019-2022](https://gtr.ukri.org/project/6D2FF57F-BE97-4070-B074-685CC802D05F). *Role: Researcher*

[Cognitive DeveLopment in the Urban Environment, MRC £618k, 2018-2021](https://gtr.ukri.org/projects?ref=MR%2FR00322X%2F1). *Role: Researcher*

[Quantitative attribution of secondary organic aerosol in Beijing to its precursors, NERC £319k, 2019-2021](https://gtr.ukri.org/projects?ref=NE%2FS006699%2F1&pn=0&fetchSize=10&selectedSortableField=date&selectedSortOrder=ASC#/tabOverview). ***Role: Case of Support writer and Researcher***

[Sources and emissions of air pollutants in Beijing, NERC £1.4m, 2016-2020](https://gtr.ukri.org/projects?ref=NE%2FN007190%2F1). *Role: Researcher*

[Human exposure to aerosol contaminants in modern microenvironments, H2020 £3.2, 2013-2016](https://cordis.europa.eu/project/id/315760/reporting). ***Role: ECR fellowship***

My publication list can be found on the Google Scholar website

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
