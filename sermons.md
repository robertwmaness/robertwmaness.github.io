---
layout: page
title: Sermons
permalink: /sermons/
---

<ul>
  {% for s in site.sermons %}
    <li><a href="{{ s.url }}">{{ s.title }}</a></li>
  {% endfor %}
</ul>
