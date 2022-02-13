---
layout: r3_main
title: rcubik Custom Mini Painting
---

<h3 style="text-align:center; margin-top:2em;">--- What Are The Haps? ---</h3>

  {% for post in site.posts limit: 5 %}
      {{ post.date| date_to_string }}: {{ post.title }}
      {{ post.excerpt }}
      <a href="{{ post.url }}">Keep reading ... </a>
  {% endfor %}

