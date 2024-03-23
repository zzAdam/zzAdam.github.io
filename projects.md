---
layout: page  # or any layout that fits your design for a list page
title: My Projects
permalink: /projects/
---

# My Projects

Here are some of my projects:

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
