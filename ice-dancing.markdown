---
layout: index
title: Ice Dancing
permalink: /ice-dancing/
---

<h1> Chinese Figure Skator Ice Dancing</h1>
<ul>


<ul>
{% for name in site.dance %}
<li><a href = "{{ name.url }}">{{ name.name }}</a></li>
{% endfor %}
</ul>