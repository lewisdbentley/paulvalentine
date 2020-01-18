---
layout: page
title: Art
---


<div class="cards">
  {% for entry in site.art %}
  <div class="card">
    <h2>
      <a href="{{ entry.url | prepend: site.baseurl }}">
        {{ entry.title }}
      </a>
    </h2>
    <p>{{ entry.content | truncatewords:14 | markdownify }}</p>
    <p><a href="{{ entry.url }}">[read more...]</a></p>
  </div>
  {% endfor %}
</div>