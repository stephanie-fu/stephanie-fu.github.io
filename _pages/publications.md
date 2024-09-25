---
layout: page
permalink: /publications/
title: publications
years: [2023, 2021]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">
<br>
The most updated publication list can be found at my [Google Scholar](https://scholar.google.com/citations?user=Rx-h05AAAAAJ&hl=en).

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
