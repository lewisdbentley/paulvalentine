---
layout: page
title: Music
---


<div class="cards">
  {% for entry in site.music reversed %}
  <div class="card">
    <h2>
      <a href="{{ entry.url | prepend: site.baseurl }}">
        {{ entry.title }}
      </a>
    </h2>
    <p>{{ entry.content | truncatewords:14 | markdownify }}</p>
    <p><a href="{{ entry.url | prepend: site.baseurl }}">[read more...]</a></p>
  </div>  
  {% endfor %}
</div>