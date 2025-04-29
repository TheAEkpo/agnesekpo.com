---
title: "PORTFOLIO"
permalink: /portfolio/
layout: splash
header:
  overlay_image: /assets/images/home.jpg
  overlay_filter: 0.3
  overlay_color: "#1D2A50"
excerpt: "Turning complex data into impactful solutions. Explore my latest projects across healthcare, fintech, and social impact."
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.gallery-item {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
  height: 250px;
}

.gallery-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.gallery-item:hover img {
  transform: scale(1.1);
}

.gallery-overlay {
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background: rgba(29, 42, 80, 0.7);
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.5s ease;
  text-align: center;
  padding: 1rem;
}

.gallery-item:hover .gallery-overlay {
  opacity: 1;
}

.gallery-buttons {
  margin-top: 1rem;
  display: flex;
  gap: 1rem;
}

.gallery-buttons a {
  background: white;
  color: #1D2A50;
  padding: 0.5rem 1rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s ease;
}

.gallery-buttons a:hover {
  background: #ccc;
}
</style>

## Project Portfolio

<div class="gallery-grid">

<div class="gallery-item">
  <img src="/assets/images/pima-indian-header.png" alt="Pima Indian Diabetes Analysis">
  <div class="gallery-overlay">
    <h3>Pima Indian Diabetes</h3>
    <p>Exploratory analysis and predictive modeling in R.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/pima-indian-diabetes-analysis" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<div class="gallery-item">
  <img src="/assets/images/ad-performance-header.png" alt="Ad Performance SQL">
  <div class="gallery-overlay">
    <h3>Ad Performance Analysis</h3>
    <p>SQL-based analysis of ad revenue and impressions.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/ad-performance-sql" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<div class="gallery-item">
  <img src="/assets/images/hospital-readmission-header.png" alt="Hospital Readmission">
  <div class="gallery-overlay">
    <h3>Hospital Readmission Prediction</h3>
    <p>Predicting patient readmission risks using ML models.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/hospital-readmission-prediction" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<!-- Add more projects here following the same structure -->

</div>
