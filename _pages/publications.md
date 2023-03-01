---
layout: page
permalink: /publications/
title: publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

(also see my [Google Scholar](https://scholar.google.com/citations?user=SvsTtDwAAAAJ&hl=en) page)

**<span>*</span>** denotes equal contribution and joint lead authorship.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>