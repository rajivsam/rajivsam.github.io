---
layout: page
permalink: /publications/
title: publications
description: These are my publications ordered by year in reverse chronological order.
years: [2022, 2021, 2020, 2019, 2018, 2017]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -q @*[year={{y}}]* %}
{% endfor %}

</div>
