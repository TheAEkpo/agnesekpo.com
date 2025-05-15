---
title: "PORTFOLIO"
permalink: /portfolio/
layout: archive
entries_layout: grid
header:
  overlay_image: /assets/images/home.jpg
  overlay_filter: 0.1
  overlay_color: "#1D2A50"
excerpt: >
  Turning complex data into impactful solutions. Explore projects across
  healthcare, business, finance, and social impact.
---

<style>
/* ───────── Grid setup ───────── */
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

/* ───────── Card ───────── */
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

/* ───────── Overlay ───────── */
.gallery-overlay {
  position: absolute;
  inset: 0;                             /* shorthand top/left/right/bottom:0 */
  background: rgba(29, 42, 80, 0.7);
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: space-between;       /* keeps button at bottom */
  align-items: center;
  text-align: center;
  padding: 1rem;
  opacity: 0;
  transition: opacity 0.5s ease;
}

.gallery-item:hover .gallery-overlay {
  opacity: 1;
}

/* ───────── Buttons ───────── */
.gallery-buttons {
  margin-top: 0;                        /* no extra push */
  width: 100%;
  display: flex;
  justify-content: center;
}

.gallery-buttons a {
  display: inline-block;
  padding: 0.55rem 1.2rem;
  font-size: 0.9rem;
  background: #ffffff;
  color: #1D2A50;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.25s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,.15);
}

.gallery-buttons a:hover {
  background: #d9d9d9;
}

/* ───────── Filter bar (optional) ───────── */
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
  color: #fff;
}
</style>

## Gallery

<div class="gallery-grid">

<!-- Ad Performance card -->
<div class="gallery-item media">
  <img src="/assets/images/revenue_by_device.png" alt="Nominal revenue by device chart">
  <div class="gallery-overlay">
    <div>
      <h3>Ad Performance & Revenue Analytics</h3>
      <p>Investigated multi-site ad logs to find top-earning devices, trace CPM trends, and flag low-fill opportunities with a rolling seven-day dashboard.</p>
    </div>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/ad-performance-revenue-analytics" target="_blank">GitHub</a>
    </div>
  </div>
</div>

<!-- Hospital Claims card -->
<div class="gallery-item healthcare">
  <img src="/assets/images/claims-cost-summary.png" alt="Cost outcome visual">
  <div class="gallery-overlay">
    <div>
      <h3>Hospital Claims: Cost, Outcomes & Readmissions</h3>
      <p>Explored synthetic hospital claims data to identify high-cost diagnoses, analyze readmission patterns, and visualize patient outcomes.</p>
    </div>
    <div class="gallery-buttons">
      <a href="https://github.com/TheAEkpo/hospital-claims-cost-outcomes" target="_blank">GitHub</a>
    </div>
  </div>
</div>

</div> <!-- /.gallery-grid -->

<!-- (Optional) JS filter logic remains unchanged -->
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
