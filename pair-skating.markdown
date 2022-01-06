---
layout: index
title: Pair Skating
permalink: /pair-skating/
---

<h1> Chinese Figure Skator Pair Skating</h1>


{% for name in site.pair %}
<a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
  <p><a href = "{{ name.url | relative_url }}">{{ name.name }}</a>
  {% endfor %}