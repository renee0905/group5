---
layout: index
title: Individual Men
permalink: /individual-men/
---

Chinese Figure Skator individual men
{% for exhibit in site.exhibits %}

<img src="{{ exhibit.img-url}}">
<p>{{ exhibit.title }}<br>{{ exhibit.birth }}<br>{{ exhibit.Personalities}}</p>

<p>{{ exhibit.video-url }}</p>
{% endfor %}