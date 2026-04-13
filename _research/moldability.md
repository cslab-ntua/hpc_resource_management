---
title: "Moldability"
permalink: /research/moldability/
layout: single
classes: wide
---

<style>
.page__content {
  max-width: 1000px;
}
</style>

Jobs with flexible resource allocation (moldable jobs) can be executed using different possible numbers of processes, selected from a set of values specified by the user. The scheduler then chooses one of these possible process counts for each job in the queue. The main components of the problem include predicting the scalability of jobs and developing optimization algorithms for selecting the appropriate number of processes per job, with the goal of satisfying one or more objective criteria. In this context, the following research directions are being pursued.

---

## Research Directions

<div class="feature__wrapper" style="margin-top: 2rem;">

  <div class="feature__item" style="flex: 1;">
    <div class="archive__item" style="padding: 1.8rem; border: 1px solid #eee; border-radius: 10px;">
      <h2 class="archive__item-title">Scheduling Algorithms</h2>
      <div class="archive__item-excerpt">
        <p>
          Designing schedulers that dynamically select the best resource allocation
          for each job based on system state and performance models.
        </p>
      </div>
      <p>
        <a href="{{ '/research/moldability/scheduling/' | relative_url }}" class="btn btn--primary btn--large">Learn more</a>
      </p>
    </div>
  </div>

  <div class="feature__item" style="flex: 1;">
    <div class="archive__item" style="padding: 1.8rem; border: 1px solid #eee; border-radius: 10px;">
      <h2 class="archive__item-title">Performance Modeling</h2>
      <div class="archive__item-excerpt">
        <p>
          Building models to predict how applications scale with resources,
          enabling better scheduling and allocation decisions.
        </p>
      </div>
      <p>
        <a href="{{ '/research/moldability/performance/' | relative_url }}" class="btn btn--primary btn--large">Learn more</a>
      </p>
    </div>
  </div>

</div>
