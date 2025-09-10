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
    <p>We’re so excited to celebrate with you in beautiful Sicily. On this site you’ll find details about the schedule, venue, how to get there, where to stay, and more. Please RSVP by <strong>April 20, 2026</strong>.</p>
  </div>
</div>

### Highlights
- Ceremony & reception at **{{ site.venue_name }}**
- Date: **{{ site.wedding_date | date: "%A, %B %e, %Y" }}**
- Location: **{{ site.venue_address }}**

[RSVP Now]({{ '/rsvp/' | relative_url }}){: .button}
