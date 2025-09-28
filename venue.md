---
layout: page
title: Venues
permalink: /venue/
---

### Ceremony
**{{ site.townhall_name }}**
{{ site.townhall_address }}

<div class="media-map-container">
  <div class="grid-item card map-item">
    <div style="position:relative;padding-top:75%">
      <iframe
      src="{{ site.townhall_map_embed_url }}"
      width="600" height="450" style="border:0;position:absolute;inset:0;width:100%;height:100%" allowfullscreen=""
      loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
  </div>
  <div class="grid-item image-item">
    <img src="{{ '/assets/img/palazzo.jpg' | relative_url }}" alt="Palazzo Ducezio" style="width:100%;height:auto;border-radius:16px;">
  </div>
</div>

### Reception
**{{ site.venue_name }}**
{{ site.venue_address }}


<div class="card">
    <div style="position:relative;padding-top:56.25%">
        <iframe
            src="{{ site.venue_map_embed_url }}"
            width="600" height="450" style="border:0;position:absolute;inset:0;width:100%;height:100%" allowfullscreen=""
            loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
</div>


<div class="card">
<h3>Notes</h3>
<ul class="list">
<li>Lorem ipsum dolor sit amet.</li>
<li>Lorem ipsum dolor sit amet.</li>
</ul>
</div>
