---
title: Notes
permalink: notes.html
---

# Notes

<ul>
  {% for post in site.categories.notes %}
    <li>
      <a href="{{ post.url }}">{{ post.excerpt }}</a>
    </li>
  {% endfor %}
</ul>

