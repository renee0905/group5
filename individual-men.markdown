---
layout: index
title: Individual Men
permalink: /individual-men/
---


<h1> Chinese Figure Skator individual men</h1>

{% for name in site.men %}
<a href = "{{ name.url | relative_url }}"><img src="{{ name.img-url }}"></a>
  <p><a href = "{{ name.url | relative_url }}">{{ name.name }}</a>
{% endfor %}

