---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2020]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% @*[year={{y}}]* %}
  {% bibliography -f papers -q %}
{% endfor %}

</div>
