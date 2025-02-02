---
layout: page
permalink: /photography/
---

<h2>Photography</h2>
<div class="photography-grid">
  {% for post in site.categories.photography %}
    <div class="photography-item">
      <a href="{{ post.url }}">
        <img src="{{ post.image }}" alt="{{ post.title }}">
        <p>{{ post.title }}</p>
      </a>
    </div>
  {% endfor %}
</div>