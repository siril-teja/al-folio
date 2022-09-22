---
layout: page
permalink: /publications/
title: publications
description: List of my [publications](https://www.researchgate.net/profile/Siril-Dukkipati/research) and ongoing work.
years: [2022, 2020, 2019, 2018]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
