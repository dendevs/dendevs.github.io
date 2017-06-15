---
title: Voyages
permalink: voyages.html
---

# Voyages 

<ul>
  {% for post in site.categories.voyages %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

