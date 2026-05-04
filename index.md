---
layout: default
title: Home
---

# Welcome to my Sandbox
Personal Sandbox for uncreative projects. Thanks for enjoying.

## Current Projects
* [Multidimensional Pong (v1.7)](/pong/index.html) — *AI-generated code*

---

## Recent Blog Posts
{% for post in site.posts %}
  * {{ post.date | date_to_string }} » [{{ post.title }}]({{ post.url }})
{% endfor %}
