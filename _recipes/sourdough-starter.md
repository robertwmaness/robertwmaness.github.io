---
layout: page
title: Recipes
permalink: /recipes/
---

<ul>
  {% for r in site.recipes %}
    <li><a href="{{ r.url }}">{{ r.title }}</a></li>
  {% endfor %}
</ul>
