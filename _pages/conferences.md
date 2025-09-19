---
layout: page
permalink: /contributions/
title: conference contributions
description: <!-- conference contributions in reversed chronological order. -->
years: [2024, 2023, 2022, 2021, 2020]
nav: false
nav_order: 5


---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>


