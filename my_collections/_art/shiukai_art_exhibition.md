---
layout: post
title: SHIUKAI ART EXHIBITION__2017
date: 6 April 2017
---


<img src="{{site.baseurl}}/assets/images/art/shiukai_art_exhibition/title.jpg">

Solo art exhibition displaying works by Shiukai Alfie @ newgatestudio

* www.shiukai.com

* Campaign manager
* Assistant-curator
* Logistics management
* Gallery assistant

{% for image in site.static_files %}
  {% if image.path contains 'assets/images/art/shiukai_art_exhibition/img' %}
  <img src="{{ image.path | prepend: site.baseurl }}" alt="">
  {% endif %}
{% endfor %}

#art #art exhibition #london #mayfair #2017