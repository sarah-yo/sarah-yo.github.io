---
layout: default
title: About Me
permalink: /
---

<div class="about-flex">
  <div class="about-desc">
    <h1 style="margin-top:0;">Bio</h1>
    <p>Sarah is a cyber security advocate working at Microsoft who engages with individuals and organizations worldwide to share her knowledge and experience in cyber security.</p>
    <p>As a cloud security expert, Sarah's mission is to educate and empower communities to do the right things securely with the technology they implement. She has also authored white papers and books on various cyber security topics and is a co-host of the popular Microsoft Azure Security Podcast.</p>
    <p>Sarah is an accomplished public speaker and has delivered presentations at various industry events including Black Hat. She is passionate about supporting the security communities across the globe and promoting diversity and inclusion in IT.</p>
    <p>For collaboration/speaking opportunities, please get in touch via the Contact page.</p>
  </div>
  <div class="about-img">
    <img src="/assets/img/sarah.jpg" alt="Sarah Young" style="max-width: 260px; width: 100%; height: auto; border-radius: 8px; box-shadow: 2px 2px 8px #eee; display: block; flex-shrink: 0;" />
  </div>
</div>

<style>
.about-flex {
  display: flex;
  align-items: center;
  gap: 32px;
  flex-wrap: wrap;
  min-height: 220px;
}
.about-desc { flex: 1; min-width: 220px; }
.about-img { flex: 0 0 260px; display: flex; align-items: center; justify-content: flex-end; }
@media (max-width: 600px) {
  .about-flex {
    flex-direction: column;
    align-items: stretch;
    gap: 18px;
  }
  .about-img {
    justify-content: center !important;
    margin: 0 auto;
    width: 100%;
  }
  .about-img img {
    margin: 0 auto !important;
    max-width: 90vw !important;
    display: block;
  }
}
</style>