---
layout: page
title: Thoughts
permalink: /thoughts/
---

<ul>
  {% for s in site.thoughts %}
    <li><a href="{{ s.url }}">{{ s.title }}</a></li>
  {% endfor %}
</ul>
