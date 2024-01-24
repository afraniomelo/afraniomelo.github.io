---
layout: page2
permalink: /ciencia/
title: titles.ciencia
description: descriptions.ciencia
years: [2024, 2023, 2022, 2021, 2019]
nav: true
---
<!-- _pages/ciencia.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

{% translate_file pages/ciencia.md %}