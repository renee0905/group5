---
title: Figure Skating Indext
layout: index
---

{% for exhibit in site.exhibits %}


<p>{{ exhibit.title }}<br>{{ exhibit.birth }}<br>{{ exhibit.Personalities}}</p>


{% endfor %}