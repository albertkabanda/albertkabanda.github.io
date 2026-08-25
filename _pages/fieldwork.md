---
title: "Fieldwork"
layout: gridlay
sitemap: false
permalink: /Fieldwork/
---

Field observations and seismic deployments are an important part of my research. These photographs document seismic station installation, servicing, data recovery, and field activities associated with my research in the East African Rift System (2022-2024).

<div class="fieldwork-gallery-wrapper">

<button class="gallery-arrow gallery-left" onclick="scrollFieldwork(-1)" aria-label="Previous photos">&#10094;</button>

<div class="fieldwork-gallery" id="fieldworkGallery">

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/IMG_1605.JPG' | relative_url }}" alt="Seismic station fieldwork">
<p>Seismic station field operations and servicing.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/IMG_1643.JPG' | relative_url }}" alt="Field operations in Uganda">
<p>Broadband seismic station servicing, 2024.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/KSSE_1714.JPG' | relative_url }}" alt="Broadband seismic station">
<p>Field operations at a temporary seismic station.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/KSSE_1741.JPG' | relative_url }}" alt="Seismic station servicing">
<p>Seismic data quality check using logpeek, passoft3, pql tools.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/servicing.jpg' | relative_url }}" alt="Seismic station servicing">
<p>Servicing and maintaining a seismic station in the field.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/servicing1.jpg' | relative_url }}" alt="Seismic station maintenance">
<p>Station maintenance and data recovery during fieldwork.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/vault.jpg' | relative_url }}" alt="Broadband seismic sensor vault">
<p>A seismic sensor vault used for broadband seismic observations.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/southwestern_rift.jpg' | relative_url }}" alt="Western Branch of the East African Rift">
<p>Rift valley setting in the southwestern Western Branch of the East African Rift | Ntoroko Region, 2024.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/BUNY_1682.JPG' | relative_url }}" alt="Seismic fieldwork in Uganda">
<p>Seismic fieldwork in western Uganda.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/rhino.jpg' | relative_url }}" alt="Rhino encountered during fieldwork">
<p>Wildlife encountered during fieldwork in western Uganda.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/elephants.jpg' | relative_url }}" alt="Elephants encountered during fieldwork">
<p>Elephants encountered during field activities in western Uganda.</p>
</div>

<div class="fieldwork-card">
<img src="{{ '/assets/fieldwork/monkeys.jpg' | relative_url }}" alt="Monkeys encountered during fieldwork">
<p>Wildlife encountered during seismic fieldwork in Uganda.</p>
</div>

</div>

<button class="gallery-arrow gallery-right" onclick="scrollFieldwork(1)" aria-label="Next photos">&#10095;</button>

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
