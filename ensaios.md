---
layout: page
title: Ensaios
permalink: /ensaios/
---

<ul>
  {% for ensaio in site.ensaios %}
    <li>
      <a href="{{ ensaio.url }}">{{ ensaio.title }}</a>
    </li>
  {% endfor %}
</ul>
