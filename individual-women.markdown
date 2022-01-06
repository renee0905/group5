---
layout: index
title: Individual Women
permalink: /individual-women/
---

<h1> Chinese Individual Women Figure Skator</h1>

{% for name in site.women %}
<a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
  <p><a href = "{{ name.url | relative_url }}">{{ name.name }}</a>
{% endfor %}

