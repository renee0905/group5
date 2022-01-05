---
layout: index
title: Pair Skating
permalink: /pair-skating/
---

<h1> Chinese Figure Skator Pair Skating</h1>
<ul>


<ul>
{% for name in site.pair %}
<li><a href = "{{ name.url }}">{{ name.name }}</a></li>
{% endfor %}
</ul>