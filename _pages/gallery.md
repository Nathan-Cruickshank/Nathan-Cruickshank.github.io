---
layout: single
title: "Photo Gallery"
permalink: /gallery/
---

<style>
  .photography-grid {
    display: grid;
    /* Automatically creates as many 250px columns as will fit on the screen */
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 2em;
  }
  
  .image-container {
    overflow: hidden; /* Keeps the zoomed image confined to its grid box */
    border-radius: 5px; /* Matches the rounded corners from your Talks page */
    background-color: #111; /* Gives a dark backdrop for the dimming effect */
  }

  .photography-grid img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Prevents images from stretching out of proportion */
    aspect-ratio: 1 / 1; /* Crops all images into uniform squares for a clean grid */
    opacity: 0.7; /* The default, slightly darker state */
    transition: all 0.3s ease-in-out; /* Smoothly animates the hover changes */
    cursor: pointer;
    display: block;
  }

  .photography-grid img:hover {
    opacity: 1; /* Snaps to full brightness */
    transform: scale(1.05); /* Zooms in 5% */
  }
</style>

<div class="photography-grid">
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
  <div class="image-container"><img src="/images/Aurora_Sky.jpg" alt="Gallery placeholder"></div>
</div>
