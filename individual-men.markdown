---
layout: index
title: Individual Men
permalink: /individual-men/
---


<h1> Chinese Figure Skator individual men</h1>
<ul>


<ul>
{% for name in site.men %}
<li><a href = "{{ name.url }}">{{ name.name }}</a></li>
{% endfor %}
</ul>
