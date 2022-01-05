---
layout: index
title: Individual Women
permalink: /individual-women/
---

<h1> Chinese Individual Women Figure Skator</h1>
<ul>


<ul>
{% for name in site.women %}
<li><a href = "{{ name.url }}">{{ name.name }}</a></li>
{% endfor %}
</ul>
