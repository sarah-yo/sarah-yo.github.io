---
layout: default
title: Contact
permalink: /contact/
---

<div class="contact-flex">
  <div class="contact-desc">
    <h1 style="margin-top:0;">Contact</h1>
    <p>If you’re interested in collaborating or having me present at your event, please get in touch by emailing me:</p>
    <p><strong>hello [at] sarahyoung [dot] io</strong></p>
  </div>
  <div class="contact-img">
    <img src="/assets/img/sarah-with-gray.jpeg" alt="Sarah with Grayson" style="max-width: 320px; width: 100%; border-radius: 10px; box-shadow: 2px 2px 12px #eee;" />
  </div>
</div>

<style>
.contact-flex {
  display: flex;
  align-items: center;
  gap: 32px;
  flex-wrap: wrap;
  min-height: 220px;
}
.contact-desc { flex: 1; min-width: 220px; }
.contact-img { flex: 0 0 320px; display: flex; align-items: center; justify-content: flex-end; }
@media (max-width: 600px) {
  .contact-flex {
    flex-direction: column;
    align-items: stretch;
    gap: 18px;
  }
  .contact-img {
    justify-content: center !important;
    margin: 0 auto;
    width: 100%;
  }
  .contact-img img {
    margin: 0 auto !important;
    max-width: 90vw !important;
    display: block;
  }
}
</style>
