---
layout: page
permalink: /publications/
title: Publications
description:
years: [2024, 2023, 2022, 2021, 2020, 2018]
nav: true
nav_order: 1
---

<div class="publications">


</div>


<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


<!-- Default Statcounter code for Publications
https://ababier.github.io/publications/ -->
<script type="text/javascript">
var sc_project=11783032; 
var sc_invisible=1; 
var sc_security="7ad292e8"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/11783032/0/7ad292e8/1/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->
