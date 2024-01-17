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

* Tese de Doutorado: [Integração Humano-Máquina para o Monitoramento de Processos Industriais Baseado em Dados](https://sucupira.capes.gov.br/sucupira/public/consultas/coleta/trabalhoConclusao/viewTrabalhoConclusao.xhtml?popup=true&id_trabalho=13725906)
* Dissertação de Mestrado: [Equilíbrio de Fases de Soluções Polidispersas de Polímeros](http://hdl.handle.net/11422/7650)
