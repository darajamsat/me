---
layout: layouts/article.md
title: The Blog
---

# Thinks I've been thinking about

<ul>
{%- for post in collections.blog reversed -%}
  <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>