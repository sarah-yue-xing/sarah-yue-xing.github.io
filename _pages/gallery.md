---
title: "Gallery"
permalink: /gallery/
layout: single
author_profile: true
---

Outside of work, I enjoy discovering new places, dancing ballet, spending time with Momo, and appreciating the small moments that make life memorable.

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin-top: 30px;
}

.gallery-card {
  background: #ffffff;
  border-radius: 6px;
  box-shadow: 0 6px 18px rgba(0,0,0,.12);
  overflow: hidden;
}

.gallery-card img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  display: block;
}

.gallery-caption {
  padding: 12px 14px;
  text-align: center;
  font-size: 0.88rem;
  line-height: 1.4;
  color: #555;
  background: #ffffff;
}

@media (max-width: 900px) {
  .gallery-grid {
    grid-template-columns: 1fr;
  }

  .gallery-card img {
    height: 260px;
  }
}
</style>




<div class="gallery-grid">

  <div class="gallery-card">
    <img src="/assets/images/conference-1.jpg" alt="CES 2026 company booth">
    <div class="gallery-caption">
      A day at CES 2026 in Las Vegas
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/ballet-1.jpg.JPG" alt="Ballet performance">
    <div class="gallery-caption">
      Dance like I’ve never danced before
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/life-1.JPG" alt="Big Island">
    <div class="gallery-caption">
      A day on the Big Island
    </div>
  </div>

  <div class="gallery-card">
      <img src="/assets/images/momo-1.jpg" alt="Momo">
    <div class="gallery-caption">
      Hide-and-seek with Momo
    </div>
  </div>

</div>
