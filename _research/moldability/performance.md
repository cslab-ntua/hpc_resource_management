---
title: "Performance Modeling"
permalink: /research/moldability/performance/
layout: single
classes: wide
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
  padding: 0.75rem 0;
  margin-bottom: 0.5rem;
  border-bottom: 1px solid var(--border-color);
}

.bibliography li:last-child {
  border-bottom: none;
}

.bib-authors {
  color: var(--text-color);
  font-size: 0.9rem;
}

.bib-title {
  font-weight: 600;
  color: var(--link-color);
  font-size: 0.9rem;
}

.bib-venue {
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
  grid-template-columns: repeat(2, 1fr);
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

/* Contact section styles */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0;
}

.contact-card {
  background: var(--background-color);
  border: 1px solid var(--border-color);
  border-radius: 12px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  text-align: center;
}

.contact-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  border-color: var(--link-color);
}

.contact-icon {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

.contact-card h3 {
  margin: 0 0 0.25rem 0;
  font-size: 1.2rem;
  color: var(--text-color);
}

.contact-role {
  color: var(--link-color);
  font-size: 0.85rem;
  font-weight: 500;
  margin-bottom: 0.5rem;
}

.contact-email {
  font-size: 0.85rem;
  word-break: break-all;
}

.contact-email a {
  color: var(--text-color-muted);
  text-decoration: none;
}

.contact-email a:hover {
  color: var(--link-color);
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 768px) {
  .tools-grid {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
}
</style>

<div class="research-content">

<h2>📊 Research Overview</h2>

<div class="research-description">
  <p>
    Study and prediction of application scalability in multi-node MPI environments based on 
    performance counters/resource consumption profiling or submission time features, using 
    real scientific applications, benchmarks, or synthetic benchmarks.
  </p>
</div>

<h2>🏷️ Keywords</h2>

<div class="keywords">
  <span class="keyword">Scalability Prediction</span>
  <span class="keyword">MPI Applications</span>
  <span class="keyword">Performance Modeling</span>
  <span class="keyword">Resource Profiling</span>
  <span class="keyword">HPC Benchmarking</span>
  <span class="keyword">Machine Learning</span>
</div>

<h2>🛠️ Tools & Development Environments</h2>

<div class="tools-grid">
  <div class="tool-card">
    <div class="tool-icon">🖥️</div>
    <h3>ARIS Supercomputer</h3>
    <p>Greek National HPC system operated by GRNET</p>
    <a href="https://doc.aris.grnet.gr/" target="_blank" class="tool-link">Learn more →</a>
  </div>
  
  <div class="tool-card">
    <div class="tool-icon">💡</div>
    <h3>Machine Learning models</h3>
    <p>Develop analytical or machine learning job scalability prediction models</p>
  </div>
  
  <div class="tool-card">
    <div class="tool-icon">📊</div>
    <h3>Performance Profiling Tools</h3>
    <p>Tools for collecting performance counters and resource usage data</p>
    <div style="margin-top: 1rem;">
      <strong>Tools:</strong>
      <ul style="margin: 0.5rem 0 0 1rem; padding: 0;">
        <li><a href="https://perfwiki.github.io/main/" target="_blank" style="color: var(--link-color);">perf tool</a></li>
        <li><a href="https://github.com/llnl/mpiP" target="_blank" style="color: var(--link-color);">mpiP tool</a></li>
      </ul>
    </div>
  </div>

  <div class="tool-card">
    <div class="tool-icon">🔧</div>
    <h3>Benchmark Suites</h3>
    <p>Standard and synthetic benchmarks for scalability evaluation</p>
    <div style="margin-top: 1rem;">
      <strong>Suites:</strong>
      <ul style="margin: 0.5rem 0 0 1rem; padding: 0;">
        <li><a href="https://www.nas.nasa.gov/software/npb.html" target="_blank" style="color: var(--link-color);">NAS Parallel Benchmarks</a></li>
        <li><a href="https://www.spec.org/hpc2021/" target="_blank" style="color: var(--link-color);">SPEC Benchmarks</a></li>
      </ul>
    </div>
  </div>
</div>

<h2>👥 Contact</h2>

<div class="contact-grid" style="grid-template-columns: repeat(2, 1fr);">
  <div class="contact-card">
    <div class="contact-icon"></div>
    <h3>Thanos Tsoukleidis-Karydakis</h3>
    <div class="contact-role">PhD Candidate</div>
    <div class="contact-email">
      <a href="mailto:ttsoukl@cslab.ece.ntua.gr">ttsoukl@cslab.ece.ntua.gr</a>
    </div>
  </div>
  <div class="contact-card">
    <div class="contact-icon"></div>
    <h3>Kostis Katsikopoulos</h3>
    <div class="contact-role">Researcher</div>
    <div class="contact-email">
      <a href="mailto:kkats@cslab.ece.ntua.gr">kkats@cslab.ece.ntua.gr</a>
    </div>
  </div>
  <div class="contact-card">
    <div class="contact-icon"></div>
    <h3>Marilena Salapa</h3>
    <div class="contact-role">Researcher</div>
    <div class="contact-email">
      <a href="mailto:msalapa@cslab.ece.ntua.gr">msalapa@cslab.ece.ntua.gr</a>
    </div>
  </div>
</div>

<h2>📚 Bibliography</h2>

<ul class="bibliography">
  <li>
    <div class="bib-authors">Calotoiu, A., Hoefler, T., Poke, M., & Wolf, F. (2013)</div>
    <div class="bib-title">"Using automated performance modeling to find scalability bugs in complex codes"</div>
    <div class="bib-venue">In Proceedings of the International Conference on High Performance Computing, Networking, Storage and Analysis (pp. 1-12)</div>
  </li>
  <li>
    <div class="bib-authors">Barnes, B. J., Rountree, B., Lowenthal, D. K., Reeves, J., De Supinski, B., & Schulz, M. (2008)</div>
    <div class="bib-title">"A regression-based approach to scalability prediction"</div>
    <div class="bib-venue">In Proceedings of the 22nd annual international conference on Supercomputing (pp. 368-377)</div>
  </li>
  <li>
    <div class="bib-authors">Antici, F., Bartolini, A., Kiziltan, Z., Babaoglu, O., & Kodama, Y. (2024)</div>
    <div class="bib-title">"McBound: An online framework to characterize and classify memory/compute-bound HPC jobs"</div>
    <div class="bib-venue">In SC24: International Conference for High Performance Computing, Networking, Storage and Analysis (pp. 1-15), IEEE</div>
  </li>
</ul>

</div>