---
layout: single
title: "Photo Gallery"
permalink: /gallery/
---

<style>
  .photography-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 15px; 
    margin-top: 2em;
  }
  
  .image-container {
    height: 250px; 
    flex-basis: 0; /* Forces widths to scale exactly to the mathematical flex-grow ratios */
    overflow: hidden;
    border-radius: 5px; 
    background-color: #111; 
  }

  .photography-grid img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Only trims the microscopic pixel fractions needed to lock the grid edges */
    opacity: 0.7; 
    transition: all 0.3s ease-in-out; 
    cursor: pointer;
    display: block;
  }

  .photography-grid img:hover {
    opacity: 1; 
    transform: scale(1.05); 
  }
  
  /* An invisible spacer to stop the final row from stretching wildly if it does not have enough images to reach the edge */
  .spacer {
    flex-grow: 10;
    height: 0;
  }
</style>

<div class="photography-grid">
  <div class="image-container" style="flex-grow: 1.5;"><img src="/images/Arcade.jpg" alt="Arcade"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Bee.jpg" alt="Bee"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Cathedral.jpg" alt="Cathedral"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Coast.jpeg" alt="Coast"></div>
  <div class="image-container" style="flex-grow: 1.33;"><img src="/images/Conservatory.jpg" alt="Conservatory"></div>
  <div class="image-container" style="flex-grow: 1.5;"><img src="/images/Mountain.jpg" alt="Mountain"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Pittsburgh.jpg" alt="Pittsburgh"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Reflection.jpeg" alt="Reflection"></div>
  <div class="image-container" style="flex-grow: 1.33;"><img src="/images/Scafell.jpeg" alt="Scafell"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Spinnaker.JPG" alt="Spinnaker"></div>
  <div class="image-container" style="flex-grow: 1.5;"><img src="/images/Sunset.JPG" alt="Sunset"></div>
  <div class="image-container" style="flex-grow: 0.67;"><img src="/images/Warrior.jpg" alt="Warrior"></div>
  <div class="spacer"></div>
</div>
