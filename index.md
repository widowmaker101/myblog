---
layout: home
title: Home
---

# Welcome to My Blog

Hi, I'm **widowmaker101**.  
This is my **live Jekyll blog** on **GitHub Pages**.

## Latest Posts
{% for post in site.posts limit:3 %}
- [**{{ post.title }}**]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All Posts →]({{ "/archive/" | relative_url }})
