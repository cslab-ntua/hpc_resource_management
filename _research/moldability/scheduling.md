---
title: "Moldable Job Scheduling"
permalink: /research/moldability/scheduling/
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
  grid-template-columns: repeat(2, 1fr);
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
  
  .contact-grid {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
}
</style>

<div class="research-content">

<h2>📊 Research Overview</h2>

<div class="research-description">
  <p>
    The goal of this work is to develop an algorithm for optimizing moldable job scheduling. The objective criteria to be optimized are the mean turnaround time (how long the user waits from job submission to completion), system throughput, and possibly energy consumption, taking into account periods of high and low demand and thus energy prices.
  </p>
</div>

<h2>🏷️ Keywords</h2>

<div class="keywords">
  <span class="keyword">Moldable Job Scheduling</span>
  <span class="keyword">Turnaround Time</span>
  <span class="keyword">System Throughput</span>
  <span class="keyword">Energy Efficiency</span>
  <span class="keyword">Dynamic Pricing</span>
  <span class="keyword">HPC Scheduling</span>
</div>

<h2>🛠️ Tools & Development Environments</h2>

<div class="tools-grid">
  <div class="tool-card">
    <div class="tool-icon">🖥️</div>
    <h3>ELiSE Emulator</h3>
    <p>Custom Python (co-)scheduling emulator</p>
    <a href="https://github.com/cslab-ntua/elise" target="_blank" class="tool-link">Learn more →</a>
  </div>

  <div class="tool-card">
    <div class="tool-icon">🖥️</div>
    <h3>Flurm Framework</h3>
    <p>Custom tool to submit the Flux RJMS as a standard batch job to the Slurm RJMS so as to test scheduling algorithms</p>
    <a href="https://github.com/cslab-ntua/flurm" target="_blank" class="tool-link">Learn more →</a>
  </div>
  
  <div class="tool-card">
    <div class="tool-icon">💡</div>
    <h3>Moldable Job Scheduling Algorithms</h3>
    <p>Develop analytical or ML-based moldable job scheduling techniques</p>
  </div>
</div>

<h2>👥 Contact</h2>

<div class="contact-grid">
  <div class="contact-card">
    <div class="contact-icon"></div>
    <h3>Thanos Tsoukleidis-Karydakis</h3>
    <div class="contact-role">PhD Candidate</div>
    <div class="contact-email">
      <a href="mailto:ttsoukl@cslab.ece.ntua.gr">ttsoukl@cslab.ece.ntua.gr</a>
    </div>
  </div>
</div>

<h2>📚 Bibliography</h2>

<ul class="bibliography">
  <li>
    <div class="bib-authors">Cirne, W., & Berman, F. (2002)</div>
    <div class="bib-title">"Using moldability to improve the performance of supercomputer jobs"</div>
    <div class="bib-venue">Journal of Parallel and Distributed Computing, 62(10), 1571-1601.</div>
  </li>
  <li>
    <div class="bib-authors">Srinivasan, S., Subramani, V., Kettimuthu, R., Holenarsipur, P., & Sadayappan, P. (2002)</div>
    <div class="bib-title">"Effective selection of partition sizes for moldable scheduling of parallel jobs"</div>
    <div class="bib-venue">In International Conference on High-Performance Computing (pp. 174-183). Berlin, Heidelberg: Springer Berlin Heidelberg.</div>
  </li>
  <li>
    <div class="bib-authors">Sabin, G., Lang, M., & Sadayappan, P. (2006)</div>
    <div class="bib-title">"Moldable parallel job scheduling using job efficiency: An iterative approach"</div>
    <div class="bib-venue">In Workshop on Job Scheduling Strategies for Parallel Processing (pp. 94-114). Berlin, Heidelberg: Springer Berlin Heidelberg.</div>
  </li>
  <li>
    <div class="bib-authors">Yang, X., Zhou, Z., Wallace, S., Lan, Z., Tang, W., Coghlan, S., & Papka, M. E. (2013)</div>
    <div class="bib-title">"Integrating dynamic pricing of electricity into energy aware scheduling for HPC systems"</div>
    <div class="bib-venue">In Proceedings of the International Conference on High Performance Computing, Networking, Storage and Analysis (pp. 1-11).</div>
  </li>
  <li>
    <div class="bib-authors">Hossain, A., Abdurahman, A., Islam, M. A., & Ahmed, K. (2025)</div>
    <div class="bib-title">"Power-aware scheduling for multi-center HPC electricity cost optimization"</div>
    <div class="bib-venue">In Workshop on Job Scheduling Strategies for Parallel Processing (pp. 1-20). Cham: Springer Nature Switzerland.</div>
  </li>
</ul>

</div>