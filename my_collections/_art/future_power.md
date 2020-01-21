---
layout: post
title: BARBICAN - FUTURE/POWER__ICA EXHIBITION__2018
date: 14th-17th February 2018
---


<img src="{{site.baseurl}}/assets/images/art/future_power/title.jpg">

14th-17th February 2018 my work was chosen to be displayed in the group exhibition:

[Future/Power] hosted by the ICA held at Croydon Art Store.


{% for image in site.static_files %}
  {% if image.path contains 'assets/images/art/future_power/img' %}
  <img src="{{ image.path | prepend: site.baseurl }}" alt="">
  {% endif %}
{% endfor %}

#ica #art exhibition #croydon