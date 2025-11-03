---
layout: home
title: Home
---

# MY TRAVEL BLOG

**2025: 6 Countries in 1 Year**

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

---

## My 2025 Africa Journey

<div class="travel-table-wrapper">
<table class="travel-table">
  <thead>
    <tr>
      <th>Country</th>
      <th>Photo</th>
      <th>Month</th>
      <th>Highlight</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Benin Republic</strong> 🇧🇯</td>
      <td><img src="/myblog/assets/images/travel/benin.jpg" alt="Benin"></td>
      <td>January</td>
      <td>Ouidah Slave Route</td>
    </tr>
    <tr>
      <td><strong>Togo</strong> 🇹🇬</td>
      <td><img src="/myblog/assets/images/travel/togo.jpg" alt="Togo"></td>
      <td>February</td>
      <td>Lomé Markets</td>
    </tr>
    <tr>
      <td><strong>Ghana</strong> 🇬🇭</td>
      <td><img src="/myblog/assets/images/travel/ghana.jpg" alt="Ghana"></td>
      <td>March</td>
      <td>Cape Coast Castle</td>
    </tr>
    <tr>
      <td><strong>Ivory Coast</strong> 🇨🇮</td>
      <td><img src="/myblog/assets/images/travel/ivorycoast.jpg" alt="Ivory Coast"></td>
      <td>May</td>
      <td>Abidjan Skyline</td>
    </tr>
    <tr>
      <td><strong>Ethiopia</strong> 🇪🇹</td>
      <td><img src="/myblog/assets/images/travel/ethiopia.jpg" alt="Ethiopia"></td>
      <td>August</td>
      <td>Lalibela Rock Churches</td>
    </tr>
    <tr>
      <td><strong>Cape Town</strong> 🇿🇦</td>
      <td><img src="/myblog/assets/images/travel/capetown.jpg" alt="Cape Town"></td>
      <td>October</td>
      <td>Table Mountain Hike</td>
    </tr>
  </tbody>
</table>
</div>

---

## 2025 Travel Stats

<div class="stats-grid">
  <a href="{{ '/2025/01/01/distance-traveled/' | relative_url }}" class="stat-card">
    <h3>10,687 km</h3>
    <p>Total Distance</p>
    <small>Click for full route</small>
  </a>
  <a href="{{ '/2025/01/02/countries-visited/' | relative_url }}" class="stat-card">
    <h3>6</h3>
    <p>Countries Visited</p>
    <small>West & East Africa</small>
  </a>
  <a href="{{ '/2025/01/03/months-on-road/' | relative_url }}" class="stat-card">
    <h3>10</h3>
    <p>Months on the Road</p>
    <small>Jan–Oct 2025</small>
  </a>
  <a href="{{ '/2025/01/04/total-flights/' | relative_url }}" class="stat-card">
    <h3>5</h3>
    <p>Total Flights</p>
    <small>Border crossings</small>
  </a>
</div>

---

## My Full 2025 Route

{% include google-maps.html %}

---

> *"I haven't been everywhere, but it's on my list."* – Susan Sontag

---

## Latest Stories
{% for post in site.posts limit:3 %}
- [**{{ post.title }}**]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All →]({{ "/archive/" | relative_url }})
