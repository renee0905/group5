---
layout: index
title: Individual Men
permalink: /individual-men/
---

Chinese Figure Skator individual men
{% for name in site.men %}

<img src="{{ exhibit.img-url}}">
<p>{{ name.name }}<br>{{ name.birth }}<br>{{ name.Personalities}}</p>

<p>{{ name.video-url }}</p>
{% endfor %}