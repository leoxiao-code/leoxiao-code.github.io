---
layout: default
title: Home
---

# Leo's English Blog

Hi, I'm Leo.  
This is my personal English blog.

## Blog posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>({{ post.date | date: "%Y-%m-%d" }})</small>
  </li>
{% endfor %}
</ul>
