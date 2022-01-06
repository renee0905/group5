---
layout: index
title: Ice Dancing
permalink: /ice-dancing/
---

<h1> Chinese Figure Skator Ice Dancing</h1>

{% for name in site.dance %}

<a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
  <p><a href = "{{ name.url | relative_url }}">{{ name.name }}</a>
{% endfor %}
