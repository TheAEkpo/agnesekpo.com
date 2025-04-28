---
title: "PORTFOLIO"
permalink: /projects/
layout: splash
header:
  overlay_image: /assets/images/home.jpg
  overlay_filter: 0.3
  overlay_color: "#1D2A50"
excerpt: "Turning complex data into impactful solutions — explore my latest projects across healthcare, fintech, and social impact."
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
}

.gallery-item img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  transition: transform 0.4s ease;
}

.gallery-item:hover img {
  transform: scale(1.05);
}

.gallery-overlay {
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background: rgba(29, 42, 80, 0.6); /* soft navy transparent */
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.4s ease;
  font-size: 1.2rem;
  font-weight: bold;
  text-align: center;
  padding: 1rem;
}

.gallery-item:hover .gallery-overlay {
  opacity: 1;
}
</style>


<div class="gallery-grid">

<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Pima-Indian-Diabetes-R" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Pima+Indian+Diabetes" alt="Pima Indian Diabetes Analysis">
  <div class="gallery-overlay">Pima Indian Diabetes (R)</div>
</a>

<!--
<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Feminence-Cycle-Tracker" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Feminence+Cycle+Tracker" alt="Feminence Cycle Tracker App">
  <div class="gallery-overlay">Feminence Cycle Tracker (C#)</div>
</a>

<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Breast-Cancer-XAI" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Breast+Cancer+XAI" alt="Breast Cancer Survival Prediction">
  <div class="gallery-overlay">Breast Cancer Survival (XAI)</div>
</a>
-->

<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Ad-Performance-SQL" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Ad+Performance+SQL" alt="Ad Performance Analysis">
  <div class="gallery-overlay">Ad Performance (SQL)</div>
</a>

<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Hospital-Readmission-Python" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Hospital+Readmission" alt="Hospital Readmission Prediction">
  <div class="gallery-overlay">Hospital Readmission (Python)</div>
</a>

<!--
<a href="https://github.com/TheAEkpo/AEkportfolio/tree/main/Housing-Access-GCGO" class="gallery-item" target="_blank">
  <img src="https://via.placeholder.com/400x250?text=Housing+Access+GCGO" alt="Housing Access Platform">
  <div class="gallery-overlay">Housing Access (GCGO)</div>
</a>
-->

</div>
