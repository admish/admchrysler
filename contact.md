---
title: Contact
layout: page
permalink: /contact/
---

<form action="https://api.web3forms.com/submit" method="POST">
  <!-- TODO(adm): replace with your Web3Forms access key (sign up with the private address; the key itself is safe to publish) -->
  <input type="hidden" name="access_key" value="Ya1c6b4f1-0bce-47f8-9ab0-98dc56dd5817">
  <input type="hidden" name="subject" value="Contact form: admchrysler.com">

  <!-- honeypot: bots fill this, humans never see it -->
  <input type="checkbox" name="botcheck" class="hidden" style="display:none;" tabindex="-1" autocomplete="off">

  <p>
    <label for="name">Name</label><br>
    <input type="text" id="name" name="name" required style="width:100%;max-width:28rem;">
  </p>
  <p>
    <label for="email">Your email</label><br>
    <input type="email" id="email" name="email" required style="width:100%;max-width:28rem;">
  </p>
  <p>
    <label for="message">Message</label><br>
    <textarea id="message" name="message" rows="6" required style="width:100%;max-width:28rem;"></textarea>
  </p>
  <p><button type="submit">Send</button></p>
</form>

<p><em>Or reach me on <a href="https://www.linkedin.com/in/adium/">LinkedIn</a>.</em></p>
