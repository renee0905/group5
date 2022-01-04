---
layout: index
title: Individual Women
permalink: /individual-women/
---

<h1> Chinese Individual Women Figure Skator</h1>
<ul>
{% for page in site.exhibits %}
<li><a href = "{{ name.url }}">{{ page.name }}</a></li>
{% endfor %}
</ul>

<ul>
{% for exhibit in site.exhibits %}
<li><a href = "{{ name.url }}">{{ exhibit.name }}</a></li>
{% endfor %}
</ul>
