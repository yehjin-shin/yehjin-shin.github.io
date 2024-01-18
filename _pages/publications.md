---
layout: page
permalink: /publications/
title: publications
description: My research interests include recommender systems and tabular data learning.
years: [2024, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
