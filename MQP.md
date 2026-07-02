---
layout: default
title: Home
description: |
    This is my senior year capstone project at WPI (known as the MQP), completed over my final year of school. I designed and manufactured all of the custom components, along with writing a large amount of the control software.

    The publication of our paper on the project can be found [in WPI's digital archive.](https://digital.wpi.edu/concern/student_works/1j92gd164)
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

## Guitar testing robot


<img src="./images/MQP/213.jpg" alt="MQP1" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/MQP/215.jpg" alt="MQP2" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/MQP/217.jpg" alt="MQP3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/MQP/218.jpg" alt="MQP3" class="thumbnail" onclick="openLightbox(this.src)">

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

