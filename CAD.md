---
layout: default
title: CAD fun
description: |
    Over my time in high school robotics, I competed in a number of 3rd party CAD competitions for FIRST Robotics Competition-style robots.
    
    I worked with 1-3 other people in each competition, with each robot designed over the course of 48 hours. I used Solidworks and later Onshape for the design, and Solidworks Visualize for the renders.

---
<style>
.thumbnail {
  border-radius: 5px;
  width: 400px;
  height: auto;
  cursor: zoom-in;
}

.lightbox-overlay {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.85);
  z-index: 1000;
  justify-content: center;
  align-items: center;
  cursor: zoom-out;
}

.lightbox-overlay.active {
  display: flex;
}

.lightbox-overlay img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 8px;
}
</style>

## CAD competition entries

* * *

This is the first robot we designed, which featured a roller-based ball collection system and an linear-motion elvator to deliver the balls. I designed the intake system and elevator power transmission.

<img src="./images/CADathon/IMG_5378.JPEG" alt="CAD1" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/CADathon/IMG_5383.JPEG" alt="CAD1.1" class="thumbnail" onclick="openLightbox(this.src)">

The next competition featured similar concepts, but involved a smaller design with a rotary ball indexer and a turret system to shoot balls into a goal. I designed the turret and intake system.

<img src="./images/CADathon/IMG_0679.JPEG" alt="CAD2" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/CADathon/IMG_0700.PNG" alt="CAD2.1" class="thumbnail" onclick="openLightbox(this.src)">

The third robot we designed was intended to pick up large discs and fire them using a turret system. I designed the pickup/turret/firing system.

<img src="./images/CADathon/IMG_1961.PNG" alt="CAD3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/CADathon/IMG_1963.PNG" alt="CAD3.1" class="thumbnail" onclick="openLightbox(this.src)">

The final robot I worked on was intended to pick up a large number of footballs and fire them out, in addition to picking up and depositing large thin donut-shaped discs. I designed the flywheel-based indexing and firing mechanism, intended to fire the footballs and give them controllable spin.

<img src="./images/CADathon/IMG_2018.JPEG" alt="CAD4" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/CADathon/IMG_2027.JPEG" alt="CAD4.1" class="thumbnail" onclick="openLightbox(this.src)">


<div class="lightbox-overlay" id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img" src="" alt="Enlarged image">
</div>

<script>
function openLightbox(src) {
  document.getElementById('lightbox-img').src = src;
  document.getElementById('lightbox').classList.add('active');
}
function closeLightbox() {
  document.getElementById('lightbox').classList.remove('active');
}
</script>

