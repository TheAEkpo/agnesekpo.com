---
title: "PORTFOLIO"
permalink: /portfolio/
layout: splash
header:
  overlay_image: /assets/images/home.jpg
  overlay_filter: 0.05
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
  flex-wrap: wrap;
  justify-content: center;
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

.filter-bar {
  text-align: center;
  margin-bottom: 2rem;
}

.filter-bar button {
  background: #f0f0f0;
  border: none;
  padding: 0.5rem 1rem;
  margin: 0 0.3rem;
  border-radius: 8px;
  font-weight: bold;
  cursor: pointer;
}

.filter-bar button.active {
  background: #1D2A50;
  color: white;
}
</style>

## Portfolio Gallery

<div class="filter-bar">
  <button data-filter="all" class="active">Show All</button>
  <button data-filter="ml">Machine Learning</button>
  <button data-filter="sql">SQL</button>
  <button data-filter="viz">Data Viz</button>
  <button data-filter="app">Apps</button>
  <button data-filter="paper">Papers</button>
</div>

<div class="gallery-grid">

<div class="gallery-item ml">
  <img src="/assets/images/pima-indian-header.png" alt="Pima Indian Diabetes">
  <div class="gallery-overlay">
    <h3>Pima Indian Diabetes</h3>
    <p>Exploratory analysis and predictive modeling in R.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/pima-indian-diabetes-analysis" target="_blank">GitHub</a>
      <a href="https://agnesekpo.com/blog/pima-indian-notebook/" target="_blank">Notebook</a>
    </div>
  </div>
</div>

<div class="gallery-item sql">
  <img src="/assets/images/ad-performance-header.png" alt="Ad Performance Analysis">
  <div class="gallery-overlay">
    <h3>Ad Performance Analysis</h3>
    <p>SQL-based analysis of ad revenue and impressions.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/ad-performance-sql" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<div class="gallery-item ml">
  <img src="/assets/images/hospital-readmission-header.png" alt="Hospital Readmission">
  <div class="gallery-overlay">
    <h3>Hospital Readmission</h3>
    <p>Predicting patient readmission risks using ML models.</p>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/hospital-readmission-prediction" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<!-- Add more projects here following the same structure -->

</div>

<script>
const filterButtons = document.querySelectorAll('.filter-bar button');
const projects = document.querySelectorAll('.gallery-item');

filterButtons.forEach(button => {
  button.addEventListener('click', () => {
    const filter = button.getAttribute('data-filter');
    filterButtons.forEach(btn => btn.classList.remove('active'));
    button.classList.add('active');

    projects.forEach(item => {
      item.style.display = (filter === 'all' || item.classList.contains(filter)) ? 'block' : 'none';
    });
  });
});
</script>
