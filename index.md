---
layout: page
title: Welcome
---

<div class="welcome-grid">
  <div class="hero-image">
    <img src="{{ '/assets/img/couple.jpg' | relative_url }}" alt="Iris & Luca" />
  </div>

  <div class="card">
    <p class="badge">Benvenuti!</p>
    <p>
    We’re so excited to celebrate with you in beautiful Sicily. On this site you’ll find details about the schedule, venue, how to get there, where to stay, and more. Please RSVP by <strong>{{ site.rsvp_deadline | date: "%A, %B %e, %Y" }}</strong>.
    </p>
  </div>
</div>

### Highlights
- Ceremony at **{{ site.venue_name }}**
- Reception at **{{ site.townhall_name }}**
- Date: **{{ site.wedding_date | date: "%A, %B %e, %Y" }}**
- Location: **{{ site.city }}, {{ site.region }}, {{ site.country }}**

[RSVP Now]({{ '/rsvp/' | relative_url }}){: .button}

---

<p class="last-updated">Last updated: {{ site.time | date: "%B %e, %Y" }}</p>
