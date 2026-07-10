---
layout: default
title: Home
description: |
    I designed parts of three FIRST Robotics Competition robots and the entirety of two FIRST tech challenge robots over my time in high school robotics. 

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

## FIRST Robotics Competition

* * *

### 2018 Season

This robot was designed to rapidly pick up and deposit milk crates using a wheeled intake and elevator system. I designed the wheel-based intake system.

<img src="./images/Real robots/IMG_1871.JPG" alt="FRC1" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Real robots/IMG_2613.JPG" alt="FRC1.1" class="thumbnail" onclick="openLightbox(this.src)">

### 2019 Season

This robot was was designed to aquire large flat discs with a central hole, and used a complex linkage system to elevate them. I designed the geometry for the linkage and the intake claw for grasping the discs.

<img src="./images/Real robots/IMG_5696.JPEG" alt="FRC2.1" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Real robots/IMG_0998.JPEG" alt="FRC2" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Real robots/IMG_5636.JPEG" alt="FRC2.2" class="thumbnail" onclick="openLightbox(this.src)">

### 2020 Season

This robot was was designed to pick up dodgeballs using a roller system and shoot them at a goal using a turret system, in addition to using a set of hooks to lift itself onto a pullup bar. I designed the arm system, which combined both the roller intake for the balls and the extendable hooks for lifting the robot.

<img src="./images/Real robots/IMG_1799.JPEG" alt="FRC3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Real robots/IMG_1826.JPEG" alt="FRC3.1" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Real robots/IMG_1783.JPEG" alt="FRC3" class="thumbnail" onclick="openLightbox(this.src)">


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

