---
layout: page
permalink: /publications/
title: research
description: (*) is used to denote equal contribution. Author order determined via one or more rounds of rock paper scissors.
years: [2022]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
