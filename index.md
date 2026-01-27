---
layout: default
title: Posts
---

{% for post in site.posts %}
- <span class="date">{{ post.date | date: "%Y-%m-%d" }}</span> [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
