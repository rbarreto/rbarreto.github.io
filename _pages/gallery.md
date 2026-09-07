---
layout: page
permalink: /gallery/
title: gallery
description: A few photos of me in the wild.
nav: true
nav_order: 5
images:
  photoswipe: true
---

<style>
  .pswp-gallery--grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
  }
  .pswp-gallery--grid a {
    display: block;
  }
  .pswp-gallery--grid img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 0.5rem;
  }
</style>

<div class="pswp-gallery pswp-gallery--grid" id="gallery--main">
  <a href="{{ '/assets/img/gallery-cltc-2019.jpg' | relative_url }}" data-pswp-width="1545" data-pswp-height="2000" target="_blank">
    <img src="{{ '/assets/img/gallery-cltc-2019.jpg' | relative_url }}" alt="Renata at a CLTC grant event, 2019" />
  </a>
  <a href="{{ '/assets/img/gallery-casual-2019.jpg' | relative_url }}" data-pswp-width="1080" data-pswp-height="720" target="_blank">
    <img src="{{ '/assets/img/gallery-casual-2019.jpg' | relative_url }}" alt="Renata, casual photo, 2019" />
  </a>
  <a href="{{ '/assets/img/gallery-algorithm-office.jpg' | relative_url }}" data-pswp-width="1500" data-pswp-height="2000" target="_blank">
    <img src="{{ '/assets/img/gallery-algorithm-office.jpg' | relative_url }}" alt="Renata at the office, standing by a conference room labeled 'Algorithm'" />
  </a>
</div>
