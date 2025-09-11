---
layout: page
title: RSVP
permalink: /rsvp/
---

Please RSVP by **{{ site.rsvp_deadline | date: "%B %e, %Y" }}**.


<form class="card" method="POST" action="{{ site.rsvp_form_action }}">
<label>Full Name<br>
<input type="text" name="name" required></label><br>
<label>Email<br>
<input type="email" name="email" required></label><br>
<label>Attending?<br>
<select name="attending" required>
<option value="Yes">Yes, wouldn’t miss it!</option>
<option value="No">Sadly can’t make it</option>
</select>
</label><br>
<label>Guests (including you)<br>
<input type="number" min="1" max="10" name="guests" value="1" required>
</label><br>
<label>Dietary Notes<br>
<textarea name="diet" rows="3" placeholder="Vegetarian, gluten-free, etc."></textarea>
</label><br>
<button class="button" type="submit">Send RSVP</button>
</form>


> **Privacy:** We only use your info for wedding planning.
