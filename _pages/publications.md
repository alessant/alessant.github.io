---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025,2024,2023,2022,2021,2020,2019,2018,2015]
nav: true
---
Here's a list of my publications in reversed chronological order. For a complete and updated list visit my [Scholar](https://scholar.google.it/citations?view_op=list_works&hl=en&hl=en&user=hblxtDYAAAAJ&sortby=pubdate&alert_preview_top_rm=2) or [DBLP](https://dblp.org/pid/173/0709.html) profile.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
