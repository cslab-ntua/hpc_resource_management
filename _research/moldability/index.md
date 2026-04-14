---
title: "Moldability"
permalink: /research/moldability/
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
  padding: 0.5rem 1rem;
  background: var(--link-color);
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: background 0.2s ease;
  text-align: center;
}

.research-card .btn:hover {
  background: var(--link-color-hover);
  text-decoration: none;
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

Jobs with flexible resource allocation (moldable jobs) can be executed using different possible numbers of processes, selected from a set of values specified by the user. The scheduler then chooses one of these possible process counts for each job in the queue. The main components of the problem include predicting the scalability of jobs and developing optimization algorithms for selecting the appropriate number of processes per job, with the goal of satisfying one or more objective criteria. In this context, the following research directions are being pursued.

---

<div class="research-directions-grid">
  
  <div class="research-card">
    <h2>Scheduling Algorithms</h2>
    <p>
      Designing schedulers that dynamically select the best resource allocation
      for each job based on system state and performance models.
    </p>
    <a href="{{ '/research/moldability/scheduling/' | relative_url }}" class="btn">Learn more →</a>
  </div>

  <div class="research-card">
    <h2>Performance Modeling</h2>
    <p>
      Building models to predict how applications scale with resources,
      enabling better scheduling and allocation decisions.
    </p>
    <a href="{{ '/research/moldability/performance/' | relative_url }}" class="btn">Learn more →</a>
  </div>
</div>