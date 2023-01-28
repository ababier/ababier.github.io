---
layout: page
permalink: /publications/
title: Publications
description:
years: [2023, 2022, 2021, 2020, 2018]
nav: true
nav_order: 1
---

<div class="publications">


<h2 class="year">{{"Preprint"}}</h2>
{% bibliography -f papers_under_review %}

</div>


<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
