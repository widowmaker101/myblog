---
layout: home
title: Home
---

# MY TRAVEL BLOG

**2025: 6 Countries in 1 Year**

---

## Countries Visited This Year

| Country         | Flag | Month     | Highlight |
|-----------------|------|-----------|-----------|
| Benin Republic  | 🇧🇯 | January   | Ouidah Slave Route |
| Togo            | 🇹🇬 | February  | Lomé Markets |
| Ghana           | 🇬🇭 | March     | Cape Coast Castle |
| Ivory Coast     | 🇨🇮 | May       | Abidjan Skyline |
| Ethiopia        | 🇪🇹 | August    | Lalibela Rock Churches |
| Cape Town       | 🇿🇦 | October   | Table Mountain Hike |

---

> *"Travel far enough, you meet yourself."* – David Mitchell

---

## Latest Adventures
{% for post in site.posts limit:3 %}
- [**{{ post.title }}**]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All Posts →]({{ "/archive/" | relative_url }})
