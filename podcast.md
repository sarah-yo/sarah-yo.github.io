---
layout: default
title: The Microsoft Azure Security Podcast
permalink: /podcast/
---

<!-- Banner with podcast logo -->
<div class="podcast-banner">
  <img src="/assets/img/podcast-logo.jpg" alt="Podcast Logo Banner" style="height:120px;width:auto;max-width:100%;object-fit:contain;" />
</div>

<div class="podcast-flex">
  <!-- Podcast image -->
  <div class="podcast-img">
    <img src="/assets/img/sarah-podcast.jpeg" alt="Sarah Young Podcast" style="height:160px;width:160px;object-fit:cover;border-radius:8px;" />
  </div>
  <div class="podcast-desc">
    <p style="font-size:1.1em;line-height:1.6;">A twice-monthly podcast dedicated to security, privacy, compliance, governance and reliability on the Microsoft cloud platform. Hosted by Microsoft security experts Michael Howard, Sarah Young, Gladys Rodriguez and Mark Simos.</p>
    <div style="display:flex;justify-content:center;margin-top:24px;">
      <a href="https://aka.ms/azsecpod" target="_blank" rel="noopener" style="background:#3b5998;color:#fff;padding:14px 36px;border-radius:6px;font-size:1.1em;text-decoration:none;box-shadow:0 2px 8px #e0e0e0;transition:background 0.2s;">Listen Now</a>
    </div>
  </div>
</div>

<style>
.podcast-banner {
  width: 100%;
  height: 140px;
  background: none;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 32px;
  border-radius: 0;
  box-shadow: none;
}
.podcast-flex {
  display: flex;
  align-items: center;
  gap: 32px;
  flex-wrap: wrap;
}
.podcast-img { flex: 0 0 180px; display: flex; align-items: center; justify-content: center; height: 180px; background: none; border-radius: 0; box-shadow: none; }
.podcast-desc { flex: 1; min-width: 220px; }
@media (max-width: 600px) {
  .podcast-banner {
    margin-bottom: 18px !important;
    height: auto !important;
    padding: 0 !important;
  }
  .podcast-flex {
    flex-direction: column;
    align-items: stretch;
    gap: 18px;
  }
  .podcast-img {
    justify-content: center !important;
    margin: 0 auto;
    width: 100%;
    height: auto !important;
    padding: 0 !important;
  }
  .podcast-img img {
    margin: 0 auto !important;
    max-width: 90vw !important;
    display: block;
  }
}
</style>