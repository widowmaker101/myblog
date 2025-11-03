---
layout: home
title: Welcome to My Blog
---

# Hi, I'm widowmaker101

I'm learning **Jekyll**, **Ruby**, and **web development** — and this is my live blog on **GitHub Pages**.

## Latest Posts
{% for post in site.posts limit:3 %}
- **[{{ post.title }}]({{ post.url }})** – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All Posts →](/myblog/archive/)

---

*Powered by [Jekyll](https://jekyllrb.com) + [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)*
