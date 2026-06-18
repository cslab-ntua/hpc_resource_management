---
title: "First Direction"
permalink: /research/coscheduling/algorithms/
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

/* Diploma Theses styles */
.theses-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0;
}

.thesis-card {
  background: var(--background-color);
  border: 1px solid var(--border-color);
  border-radius: 12px;
  padding: 1.5rem;
  transition: all 0.3s ease;
}

.thesis-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  border-color: var(--link-color);
}

.thesis-title a {
  color: var(--link-color);
  text-decoration: none;
  transition: color 0.2s ease;
}

.thesis-title a:hover {
  color: var(--link-color-hover);
  text-decoration: underline;
}

.thesis-author {
  color: var(--text-color);
  font-size: 0.9rem;
  margin-bottom: 0.25rem;
}

.thesis-date {
  color: var(--text-color-muted);
  font-size: 0.8rem;
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
  
  .theses-grid {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
}
</style>

<div class="research-content">

<h2>📊 Research Overview</h2>

<div class="research-description">
  <p>
    The goal of this work is to develop new algorithms for smarter job co-scheduling, leveraging knowledge of application behavior using the ELiSE simulator, while taking into account straggler effects or job speedups derived from prediction models. Developed algorithms can then be tested in a real-world setting using the Flurm framework.
  </p>
</div>

<h2>🏷️ Keywords</h2>

<div class="keywords">
  <span class="keyword">Co-Scheduling</span>
  <span class="keyword">Makespan</span>
  <span class="keyword">Turnaround Time</span>
  <span class="keyword">Speedup</span>
  <span class="keyword">Straggler Effect</span>
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
</div>

<h2>👥 Contact</h2>

<div class="contact-grid">
  <div class="contact-card">
    <div class="contact-icon"></div>
    <h3>Nikos Triantafyllis</h3>
    <div class="contact-role">PhD Candidate</div>
    <div class="contact-email">
      <a href="mailto:ntriantafyl@cslab.ece.ntua.gr">ntriantafyl@cslab.ece.ntua.gr</a>
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
</div>

<h2>📜 Relevant Completed Diploma Theses</h2>

<div class="theses-grid">
  <div class="thesis-card">
    <div class="thesis-title">
      <a href="http://artemis.cslab.ece.ntua.gr:8080/jspui/handle/123456789/19554" target="_blank">Co-scheduling algorithms for HPC applications</a>
    </div>
    <div class="thesis-author">Myrsini Kellari</div>
    <div class="thesis-date">2025</div>
  </div>
  
  <div class="thesis-card">
    <div class="thesis-title">
      <a href="http://artemis.cslab.ece.ntua.gr:8080/jspui/handle/123456789/18315" target="_blank">Implementation of a virtual resource manager for MPI applications in high-performance computing (HPC) systems</a>
    </div>
    <div class="thesis-author">Alexios Papavasileiou</div>
    <div class="thesis-date">2022</div>
  </div>
</div>

<h2>📚 Bibliography</h2>

<ul class="bibliography">
  <li>
    <div class="bib-authors">Authors</div>
    <div class="bib-title">"Title"</div>
    <div class="bib-venue">Venue</div>
  </li>
  <li>
    <div class="bib-authors">Authors</div>
    <div class="bib-title">"Title"</div>
    <div class="bib-venue">Venue</div>
  </li>
  <li>
    <div class="bib-authors">Authors</div>
    <div class="bib-title">"Title"</div>
    <div class="bib-venue">Venue</div>
  </li>
  <li>
    <div class="bib-authors">Authors</div>
    <div class="bib-title">"Title"</div>
    <div class="bib-venue">Venue</div>
  </li>
  <li>
    <div class="bib-authors">Authors</div>
    <div class="bib-title">"Title"</div>
    <div class="bib-venue">Venue</div>
  </li>
</ul>

</div>