---
title: "Performance Modeling"
permalink: /research/moldability/performance/
layout: single
---

<style>
/* Performance modeling page styles */
.research-content {
  max-width: 100%;
}

.research-section {
  margin-bottom: 2.5rem;
}

.section-title {
  font-size: 1.8rem;
  margin-bottom: 1rem;
  border-bottom: 3px solid var(--link-color);
  display: inline-block;
  padding-bottom: 0.3rem;
}

.research-description {
  background: var(--background-secondary);
  border-left: 4px solid var(--link-color);
  padding: 1.5rem;
  border-radius: 8px;
  margin: 1.5rem 0;
  font-size: 1.05rem;
  line-height: 1.7;
}

.research-description p {
  margin: 0;
}

.methods-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0;
}

.method-card {
  background: var(--background-color);
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 1rem;
  text-align: center;
  transition: all 0.2s ease;
}

.method-card:hover {
  transform: translateY(-2px);
  border-color: var(--link-color);
}

.method-icon {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
}

.method-card p {
  margin: 0;
  font-size: 0.9rem;
  color: var(--text-color-muted);
}

.bibliography {
  list-style: none;
  padding: 0;
  margin: 1rem 0;
}

.bibliography li {
  padding: 1rem;
  margin-bottom: 1rem;
  background: var(--background-secondary);
  border-radius: 8px;
  border-left: 3px solid var(--link-color);
  transition: all 0.2s ease;
}

.bibliography li:hover {
  transform: translateX(5px);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.bibliography li p {
  margin: 0;
  font-size: 0.9rem;
  line-height: 1.5;
}

.bib-title {
  font-weight: 600;
  color: var(--text-color);
}

.bib-authors, .bib-venue {
  color: var(--text-color-muted);
  font-size: 0.85rem;
}

.keywords {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 1rem 0;
}

.keyword {
  background: var(--background-secondary);
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 0.8rem;
  color: var(--link-color);
  border: 1px solid var(--border-color);
}

/* Tools & Environments section */
.tools-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0;
}

.tool-card {
  background: var(--background-color);
  border: 1px solid var(--border-color);
  border-radius: 12px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  text-decoration: none;
  display: block;
}

.tool-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
  border-color: var(--link-color);
}

.tool-icon {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.tool-card h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.3rem;
  color: var(--text-color);
}

.tool-card p {
  color: var(--text-color-muted);
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.5;
}

.tool-link {
  display: inline-block;
  margin-top: 1rem;
  color: var(--link-color);
  font-size: 0.85rem;
  font-weight: 500;
  text-decoration: none;
}

.tool-link:hover {
  text-decoration: underline;
}
</style>

<div class="research-content">

## 📊 Research Overview

<div class="research-description">
  <p>
    Study and prediction of application scalability in multi-node MPI environments based on 
    performance counters/resource consumption profiling or submission time features, using 
    real scientific applications, benchmarks, or synthetic benchmarks.
  </p>
</div>

### 🔬 Key Approaches

<div class="methods-grid">
  <div class="method-card">
    <div class="method-icon">📊</div>
    <p>Performance Counters & Resource Profiling</p>
  </div>
  <div class="method-card">
    <div class="method-icon">⏱️</div>
    <p>Submission Time Features</p>
  </div>
  <div class="method-card">
    <div class="method-icon">⚙️</div>
    <p>Real Scientific Applications</p>
  </div>
  <div class="method-card">
    <div class="method-icon">📈</div>
    <p>Benchmarks & Synthetic Workloads</p>
  </div>
</div>

### 🏷️ Keywords

<div class="keywords">
  <span class="keyword">Scalability Prediction</span>
  <span class="keyword">MPI Applications</span>
  <span class="keyword">Performance Modeling</span>
  <span class="keyword">Resource Profiling</span>
  <span class="keyword">HPC Benchmarking</span>
</div>

## 🛠️ Tools & Development Environments

<div class="tools-grid">
  <div class="tool-card">
    <div class="tool-icon">🖥️</div>
    <h3>ARIS Supercomputer</h3>
    <p>Greek National HPC system operated by GRNET, featuring Intel Xeon Gold processors, NVIDIA GPUs, and high-speed InfiniBand interconnect.</p>
    <a href="https://hpc.grnet.gr/aris/" target="_blank" class="tool-link">Learn more →</a>
  </div>
</div>

## 📚 Bibliography

<ul class="bibliography">
  <li>
    <p class="bib-title">Using automated performance modeling to find scalability bugs in complex codes</p>
    <p class="bib-authors">Calotoiu, A., Hoefler, T., Poke, M., & Wolf, F.</p>
    <p class="bib-venue">In Proceedings of the International Conference on High Performance Computing, Networking, Storage and Analysis (pp. 1-12), 2013.</p>
  </li>
  <li>
    <p class="bib-title">A regression-based approach to scalability prediction</p>
    <p class="bib-authors">Barnes, B. J., Rountree, B., Lowenthal, D. K., Reeves, J., De Supinski, B., & Schulz, M.</p>
    <p class="bib-venue">In Proceedings of the 22nd annual international conference on Supercomputing (pp. 368-377), 2008.</p>
  </li>
  <li>
    <p class="bib-title">McBound: An online framework to characterize and classify memory/compute-bound HPC jobs</p>
    <p class="bib-authors">Antici, F., Bartolini, A., Kiziltan, Z., Babaoglu, O., & Kodama, Y.</p>
    <p class="bib-venue">In SC24: International Conference for High Performance Computing, Networking, Storage and Analysis (pp. 1-15), IEEE, 2024.</p>
  </li>
</ul>

</div>