---
title: "Co-Scheduling"
permalink: /research/coscheduling/
layout: single
classes: wide
top_level: true
---

<style>
.page__content {
  max-width: 1000px;
  margin: 0 auto;
}

.research-directions-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin-top: 2.5rem;
}

.research-card {
  padding: 2rem;
  border: 1px solid var(--border-color);
  border-radius: 12px;
  background: var(--background-color);
  transition: all 0.3s ease;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.research-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
  border-color: var(--link-color);
}

.research-card h2 {
  margin-bottom: 1rem;
  font-size: 1.5rem;
  color: var(--text-color);
}

.research-card p {
  color: var(--text-color-muted);
  line-height: 1.6;
  flex-grow: 1;
}

.research-card .btn {
  display: inline-block;
  margin-top: 1.5rem;
  padding: 0.75rem 1.5rem;
  background-color: #0066cc;
  color: white !important;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  font-size: 0.9rem;
  transition: background-color 0.2s ease;
  text-align: center;
  border: none;
  cursor: pointer;
}

.research-card .btn:hover {
  background-color: #004999;
  text-decoration: none;
  transform: translateX(3px);
}

/* Responsive: Stack to 1 column on mobile */
@media (max-width: 768px) {
  .research-directions-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
}
</style>

## Research Overview

Studies show that co-execution, i.e., running different applications simultaneously on the same node, leads to more efficient use of computational resources. The selection of which applications will run together plays a significant role in execution performance due to the race conditions that develop depending on the resources each application demands. The main focus of research in this area is the study, simulation, implementation, and evaluation of co-scheduling algorithms aimed at optimizing metrics such as system throughput and energy efficiency. This area focuses on intelligent co-scheduling of multiple jobs, with the goal of optimizing system performance and user experience.

---

<div class="research-directions-grid">
  
  <div class="research-card">
    <h2>Co-Scheduling Algorithms</h2>
    <p>
        Designing new algorithms for smarter co-scheduling of jobs with the intent to minimize straggler effects or take advantage of job speedup predictions
    </p>
    <a href="{{ '/research/coscheduling/algorithms/' | relative_url }}" class="btn">Learn more →</a>
  </div>

  <div class="research-card">
    <h2>ELiSE Extensions</h2>
    <p>
        Extend the ELiSE emulator with new features, such as quarter-socket allocation for co-scheduling
    </p>
    <a href="{{ '/research/coscheduling/elise_extensions/' | relative_url }}" class="btn">Learn more →</a>
  </div>

  <div class="research-card">
    <h2>Co-Location Behavior Prediction</h2>
    <p>
        Predict the behavior of an application under co-location with analytical or ML methods
    </p>
    <a href="{{ '/research/coscheduling/modeling/' | relative_url }}" class="btn">Learn more →</a>
  </div>

  <div class="research-card">
    <h2>Flux Extensions</h2>
    <p>
        Extend the Flux next-generation resource manager with new features
    </p>
    <a href="{{ '/research/coscheduling/flux/' | relative_url }}" class="btn">Learn more →</a>
  </div>

  <div class="research-card">
    <h2>Quarter-Socket Co-Scheduling in a real supercomputer</h2>
    <p>
        Study the quarter-socket co-location of MPI applications in a real HPC system
    </p>
    <a href="{{ '/research/coscheduling/quarter/' | relative_url }}" class="btn">Learn more →</a>
  </div>
</div>