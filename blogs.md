---
layout: page
permalink: /blogs/
---

<h2 style="padding-left: 2%;">Blog Posts</h2>
<ul>
  {% for post in site.categories.blog %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>