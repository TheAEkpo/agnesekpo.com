---
title: "PORTFOLIO"
permalink: /portfolio/
layout: splash
header:
  overlay_image: /assets/images/home.jpg
  overlay_filter: 0.1
  overlay_color: "#1D2A50"
excerpt: >
  Turning complex data into impactful solutions. Explore projects across
  healthcare, business, finance, and social impact.
---

<style>
/* ───────────── Gallery grid ───────────── */
.gallery-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:2rem;
  margin-top:2rem;
}

/* ───────────── Card wrapper ───────────── */
.gallery-item{
  position:relative;
  display:block;                 /* anchor behaves like a block card   */
  overflow:hidden;
  border-radius:10px;
  height:250px;
  cursor:pointer;
  text-decoration:none;          /* no link underline                  */
}

.gallery-item img{
  width:100%;height:100%;
  object-fit:cover;
  transition:transform .5s ease;
}
.gallery-item:hover img{transform:scale(1.1);}

/* ───────────── Overlay ───────────── */
.gallery-overlay{
  position:absolute;inset:0;
  background:rgba(29,42,80,.72);
  color:#fff;
  display:flex;flex-direction:column;
  justify-content:space-between; /* text top - pill bottom             */
  align-items:center;
  text-align:center;
  padding:1rem;
  opacity:0;transition:opacity .45s ease;
}
.gallery-item:hover .gallery-overlay{opacity:1;}

/* ───────────── Button pill (span, not <a>) ───────────── */
.gallery-buttons span{
  display:inline-block;
  padding:.55rem 1.25rem;
  background:#fff;
  color:#1D2A50;
  border-radius:8px;
  font-weight:600;
  font-size:.9rem;
  box-shadow:0 2px 4px rgba(0,0,0,.15);
  pointer-events:none;           /* pill is visual; whole card clicks  */
}
</style>

## Gallery

<div class="gallery-grid">

<!-- ══════════ CARD 1 ══════════ -->
<a class="gallery-item media"
   href="https://github.com/TheAEkpo/ad-performance-revenue-analytics"
   target="_blank">
  <img src="/assets/images/revenue_by_device.png"
       alt="Nominal revenue by device chart">
  <div class="gallery-overlay">
    <div>
      <h3>Ad Performance &amp; Revenue Analytics</h3>
      <p>
        Investigated multi-site ad logs to surface top-earning devices,
        trace CPM trends, and flag low-fill opportunities with a rolling
        seven-day dashboard.
      </p>
    </div>
    <div class="gallery-buttons"><span>GitHub</span></div>
  </div>
</a>

<!-- ══════════ CARD 2 ══════════ -->
<a class="gallery-item healthcare"
   href="https://github.com/TheAEkpo/hospital-claims-cost-outcomes"
   target="_blank">
  <img src="/assets/images/claims-cost-summary.png"
       alt="Hospital claims cost outcome heatmap">
  <div class="gallery-overlay">
    <div>
      <h3>Hospital Claims: Cost, Outcomes &amp; Readmissions</h3>
      <p>
        Analysed synthetic hospital claims to identify high-cost
        diagnoses, readmission patterns, and patient-outcome drivers.
      </p>
    </div>
    <div class="gallery-buttons"><span>GitHub</span></div>
  </div>
</a>

<!-- ════════ TEMPLATE FOR NEW PROJECTS ════════
<a class="gallery-item CATEGORY"
   href="https://github.com/USERNAME/REPO"
   target="_blank">
  <img src="/assets/images/IMAGE.png" alt="ALT TEXT">
  <div class="gallery-overlay">
    <div>
      <h3>Project Title</h3>
      <p>One-sentence description of what you built.</p>
    </div>
    <div class="gallery-buttons"><span>GitHub</span></div>
  </div>
</a>
═════════════════════════════════════════════ -->

</div><!-- /.gallery-grid -->
