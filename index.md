---
layout: home
title: Home
---

# MY TRAVEL BLOG

**2025: 6 Countries in 1 Year**

---

## My 2025 Africa Journey

| Country         | Photo | Month     | Highlight |
|-----------------|-------|-----------|-----------|
| **Benin Republic** | ![Benin](/myblog/assets/images/travel/benin.jpg) | January | Ouidah Slave Route |
| **Togo** | ![Togo](/myblog/assets/images/travel/togo.jpg) | February | Lomé Markets |
| **Ghana** | ![Ghana](/myblog/assets/images/travel/ghana.jpg) | March | Cape Coast Castle |
| **Ivory Coast** | ![Ivory Coast](/myblog/assets/images/travel/ivorycoast.jpg) | May | Abidjan Skyline |
| **Ethiopia** | ![Ethiopia](/myblog/assets/images/travel/ethiopia.jpg) | August | Lalibela Rock Churches |
| **Cape Town** | ![Cape Town](/myblog/assets/images/travel/capetown.jpg) | October | Table Mountain Hike |

---

> *"Not all those who wander are lost."* – J.R.R. Tolkien

---

## Latest Stories
{% for post in site.posts limit:3 %}
- [**{{ post.title }}**]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All →]({{ "/archive/" | relative_url }})
