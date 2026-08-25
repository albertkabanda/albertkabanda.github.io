---
title: "Fieldwork"
layout: gridlay
sitemap: false
permalink: /Fieldwork/
---

# Fieldwork

Field observations and seismic deployments are an important part of my research. These photographs document seismic station installation, servicing, data recovery, and field activities associated with my research in the East African Rift System.

<div class="fieldwork-gallery-wrapper">

  <button class="gallery-arrow gallery-left" onclick="scrollFieldwork(-1)" aria-label="Previous photos">
    &#10094;
  </button>

  <div class="fieldwork-gallery" id="fieldworkGallery">

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/BUNY_1682.JPG' | relative_url }}" alt="Fieldwork in Uganda">
      <p>Seismic fieldwork in western Uganda.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/HOIM_1605.jpeg' | relative_url }}" alt="Seismic field deployment">
      <p>Field deployment in the northern Western Branch of the East African Rift.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/IMG_1605.JPG' | relative_url }}" alt="Seismic station fieldwork">
      <p>Seismic station installation and field operations.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/IMG_1643.JPG' | relative_url }}" alt="Field operations in Uganda">
      <p>Field operations during seismic network deployment.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/KSSE_1714.JPG' | relative_url }}" alt="Broadband seismic station">
      <p>Broadband seismic station installation and servicing.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/KSSE_1741.JPG' | relative_url }}" alt="Seismic station servicing">
      <p>Servicing a seismic station during field deployment.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/rhino.jpg' | relative_url }}" alt="Rhino Graben fieldwork">
      <p>Fieldwork in the Rhino Graben, northern Western Branch of the East African Rift.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/servicing.jpg' | relative_url }}" alt="Seismic station servicing">
      <p>Servicing and maintaining a temporary seismic station.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/servicing1.jpg' | relative_url }}" alt="Field station maintenance">
      <p>Field maintenance and data recovery from a seismic station.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/southwestern_rift.jpg' | relative_url }}" alt="Southwestern East African Rift">
      <p>Field observations in the southwestern part of the Western Branch.</p>
    </div>

    <div class="fieldwork-card">
      <img src="{{ '/assets/fieldwork/vault.jpg' | relative_url }}" alt="Seismic sensor vault">
      <p>A seismic sensor vault used for broadband seismic observations.</p>
    </div>

  </div>

  <button class="gallery-arrow gallery-right" onclick="scrollFieldwork(1)" aria-label="Next photos">
    &#10095;
  </button>

</div>


<style>

.fieldwork-gallery-wrapper {
  position: relative;
  width: 100%;
  margin: 35px 0 50px 0;
}

.fieldwork-gallery {
  display: flex;
  gap: 20px;
  overflow-x: auto;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
  padding: 10px 5px 25px 5px;

  /* Hide scrollbar */
  scrollbar-width: none;
  -ms-overflow-style: none;
}

.fieldwork-gallery::-webkit-scrollbar {
  display: none;
}

.fieldwork-card {
  flex: 0 0 72%;
  max-width: 720px;
  scroll-snap-align: center;
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0,0,0,0.15);
}

.fieldwork-card img {
  width: 100%;
  height: 450px;
  object-fit: contain;
  background: #f4f4f4;
  display: block;
}

.fieldwork-card p {
  margin: 0;
  padding: 14px 18px 16px 18px;
  font-size: 0.95rem;
  line-height: 1.5;
  text-align: center;
}

.gallery-arrow {
  position: absolute;
  top: 45%;
  transform: translateY(-50%);
  z-index: 10;

  width: 48px;
  height: 48px;

  border: none;
  border-radius: 50%;

  background: rgba(0,0,0,0.65);
  color: white;

  font-size: 25px;
  font-weight: bold;

  cursor: pointer;
}

.gallery-arrow:hover {
  background: rgba(0,0,0,0.9);
}

.gallery-left {
  left: 12px;
}

.gallery-right {
  right: 12px;
}


/* Mobile */

@media (max-width: 768px) {

  .fieldwork-card {
    flex: 0 0 92%;
  }

  .fieldwork-card img {
    height: 320px;
  }

  .gallery-arrow {
    width: 40px;
    height: 40px;
    font-size: 20px;
  }

}

</style>


<script>

function scrollFieldwork(direction) {

  const gallery = document.getElementById("fieldworkGallery");

  const amount = gallery.clientWidth * 0.75;

  gallery.scrollBy({
    left: direction * amount,
    behavior: "smooth"
  });

}

</script>
