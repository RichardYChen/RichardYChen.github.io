---
layout: page
permalink: /papers/
title: Papers
description: generated by <a href=https://github.com/inukshuk/jekyll-scholar target=_blank>jekyll-scholar</a>
years: [2024, 2020, 2019, 2018, 2017]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

[comment]: <> #### Research summary
