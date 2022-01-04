---
title: Figure Skating Indext
layout: index
---

{% for exhibit in site.exhibits %}


<p>{{ exhibit.name }}<br>{{ exhibit.birth }}<br>{{ exhibit.Personalities}}</p>


{% endfor %}