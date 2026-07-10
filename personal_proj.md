---
layout: default
title: Home
description: |
    I have done a variety of less-structured design work, including several personal projects and ideas I have worked on, in addition to some freelance work.

---
<style>
.thumbnail {
  border-radius: 5px;
  width: 300px;
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

## Independent projects

 * * *
### Phone-as-webcam mount for any monitor size
Most smartphones can double as a webcam for video conferencing, which gives excellent video quality and eliminates the need for more peripherals. I designed a mount for an iPhone that could interface with a variety of monitors thanks to an adjustable leg.

<img src="./images/Projects/image1.jpeg" alt="PhoneHolder2" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/IMG_1965.jpeg" alt="Phoneholder3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/image0.jpeg" alt="Phoneholder1" class="thumbnail" onclick="openLightbox(this.src)">

### Hemispherical speaker housing
A local connection I had needed to repair a set of unusually-shaped speaker housings, which essentially use a piece of fabric stretched over a colander-like structure to cover the actual speaker drivers. I designed new structures that could be easily printed using my prusa mini while still retaining the original shape.

<img src="./images/Projects/20210101_233548.jpg" alt="Speakermount3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/IMG_2931.JPEG" alt="SpeakerMount" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/IMG_2939.JPEG" alt="Speakermount3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/IMG_2976.JPEG" alt="Speakermount2" class="thumbnail" onclick="openLightbox(this.src)">


### Misc projects

A custom 3D printed phone case:
<img src="./images/Projects/IMG_0794.JPEG" alt="Phonecase" class="thumbnail" onclick="openLightbox(this.src)">

A 3D printed orbital gearbox, to understand how 3D printing tolerances affect gear mesh & tooth profiles:

<img src="./images/Projects/IMG_2748.JPEG" alt="Speakermount3" class="thumbnail" onclick="openLightbox(this.src)">
<img src="./images/Projects/IMG_2749.JPEG" alt="Speakermount3" class="thumbnail" onclick="openLightbox(this.src)">


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



