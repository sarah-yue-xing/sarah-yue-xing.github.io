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
  gap: 28px;
  margin-top: 30px;
}

.gallery-card {
  background: #ffffff;
  box-shadow: 0 4px 12px rgba(0,0,0,.18);
  overflow: hidden;
}

.gallery-card img {
  width: 100%;
  height: 320px;
  object-fit: cover;
  display: block;
}

.gallery-caption {
  padding: 10px;
  text-align: center;
  font-size: 0.9rem;
  color: #555;
}

@media (max-width: 900px) {
  .gallery-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="gallery-grid">

  <div class="gallery-card">
    <img src="/assets/images/gallery/conference-1.jpg" alt="Conference">
    <div class="gallery-caption">
      A day at CES 2026 in Las Vegas
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/gallery/ballet-01.jpg" alt="Ballet">
    <div class="gallery-caption">
      Dance like I've never danced before.
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/gallery/life-1.JPG" alt="Big Island">
    <div class="gallery-caption">
      A day on the Big Island.
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/gallery/momo-1.jpg" alt="Momo">
    <div class="gallery-caption">
      Hide-and-seek with Momo.
    </div>
  </div>

</div>
