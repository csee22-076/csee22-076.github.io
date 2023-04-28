---
title: "Posts by Category"
permalink: /categories/
toc: true
toc_sticky: true
---

{% assign posts = site.categories %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}