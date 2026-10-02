---
layout: single
title: "Photo Gallery"
permalink: /gallery/
---

<style>
  .photography-grid {
    column-count: 2; 
    column-gap: 20px;
    margin-top: 2em;
  }
  
  .image-container {
    margin-bottom: 20px; 
    break-inside: avoid; 
    overflow: hidden; 
    border-radius: 5px; 
    background-color: #111; 
  }

  .photography-grid img {
    width: 100%;
    height: auto; /* Allows every photo to dictate its true, uncropped height */
    opacity: 0.7; 
    transition: all 0.3s ease-in-out; 
    cursor: pointer;
    display: block;
    
    /* Forces Hardware/GPU acceleration to fix animation lag */
    will-change: transform, opacity;
    transform: translateZ(0); 
  }

  .photography-grid img:hover {
    opacity: 1; 
    transform: scale(1.05) translateZ(0); 
  }
  /* Forces full brightness and disables hover zoom on touch devices */
  @media (hover: none) {
    .photography-grid img {
      opacity: 1;
    }
    .photography-grid img:hover {
      transform: none;
    }
  }
</style>

<div class="photography-grid">
  <div class="image-container"><img src="/images/Arcade.jpg" alt="Arcade"></div>
  <div class="image-container"><img src="/images/Bee.jpg" alt="Bee"></div>
  <div class="image-container"><img src="/images/Cathedral.jpg" alt="Cathedral"></div>
  <div class="image-container"><img src="/images/Coast.jpeg" alt="Coast"></div>
  <div class="image-container"><img src="/images/Conservatory.jpg" alt="Conservatory"></div>
  <div class="image-container"><img src="/images/Mountain.jpg" alt="Mountain"></div>
  <div class="image-container"><img src="/images/Pittsburgh.jpg" alt="Pittsburgh"></div>
  <div class="image-container"><img src="/images/Reflection.jpeg" alt="Reflection"></div>
  <div class="image-container"><img src="/images/Scafell.jpeg" alt="Scafell"></div>
  <div class="image-container"><img src="/images/Spinnaker.JPG" alt="Spinnaker"></div>
  <div class="image-container"><img src="/images/Sunset.JPG" alt="Sunset"></div>
  <div class="image-container"><img src="/images/Warrior.jpg" alt="Warrior"></div>
</div>
