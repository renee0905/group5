---
title: Figure Skating Indext
layout: index
---

{% for name in site.men %}


<p>{{ name.name }}<br>{{ name.birth }}<br>{{ name.Personalities}}</p>


{% endfor %}