---
layout: page
permalink: /workshop presentations/
title: workshop presentations
description: This page presents Workshop or Conference papers which is not a official terminal publication (i.e. on-going research). Note that the "DesignCon" is top-tiered SI/PI non-published venue. (*) is used to denote equal contribution. 
years: [2023,2022,2021,2020]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f workshops -q @*[year={{y}}]* %}
{% endfor %}

</div>
