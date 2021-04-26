---
layout: page
permalink: /research/
title: publications & research 
rank: 2
description: My Publications and Key Research. 
years: [2021, 2020, 2019]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
