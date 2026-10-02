---
layout: single
title: "Photo Gallery"
permalink: /gallery/
---

<style>
  .photography-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 15px; /* The space between your photos */
    margin-top: 2em;
  }
  
  .image-container {
    height: 250px; /* The baseline target height for your rows */
    flex-grow: 1; /* Tells the container to stretch and fill any empty space in the row */
    overflow: hidden;
    border-radius: 5px; /* Matches the rounded corners from your Talks page */
    background-color: #111; /* Gives a dark backdrop for the dimming effect */
  }

  .photography-grid img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures the image fills its stretched box beautifully without distorting */
    opacity: 0.7; /* The default, slightly darker state */
    transition: all 0.3s ease-in-out; /* Smoothly animates the hover changes */
    cursor: pointer;
    display: block;
  }

  .photography-grid img:hover {
    opacity: 1; /* Snaps to full brightness */
    transform: scale(1.05); /* Zooms in 5% */
  }
  
  /* Stops the final row from stretching wildly if it only contains 1 or 2 leftover images */
  .image-container:last-child {
    flex-grow: 0;
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
