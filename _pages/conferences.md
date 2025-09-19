---
layout: page
permalink: /contributions/
title: contributions
description: <!-- conference contributions in reversed chronological order. -->
years: [2024, 2023, 2021, 2020]
nav: true
nav_order: 5


---

Talks and posters contributed to conferences and seminars.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>


