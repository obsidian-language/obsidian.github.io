---
layout: default
title: Change Log
permalink: /changelog/
---

# Change Log

{% for post in site.posts %}
- **{{ post.date | date: "%Y-%m-%d" }}** – [{{ post.title }}]({{ post.url }})
{% endfor %}
