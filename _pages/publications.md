---
layout: page2
permalink: /ciencia/
title: titles.publications
description: descriptions.publications
years: [2023, 2022, 2021, 2019]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

{% translate_file pages/publications.md %}