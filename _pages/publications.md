---
layout: profile
title: Publication
permalink: /publications/
eyebrow: Research output
subtitle: Publications and working papers in stochastic optimization, decomposition, and power systems.
---

<div class="paper-tools">
  <p>Find my citation record on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.</p>
  <nav aria-label="Publication sections"><a href="#published">Published &amp; accepted</a><a href="#working-papers">Working papers</a></nav>
</div>
<p class="paper-authors">⋆ denotes the corresponding author.</p>
<section class="paper-section" id="published" aria-labelledby="published-heading">
  {% assign published = site.data.research | where: 'group', 'published' %}
  <h2 class="paper-section-heading" id="published-heading">Published &amp; accepted <small>{{ published.size }}</small></h2>
  <ul class="paper-list">
    {% for paper in published %}{% include research-item.html %}{% endfor %}
  </ul>
</section>
<section class="paper-section" id="working-papers" aria-labelledby="working-heading">
  {% assign working = site.data.research | where: 'group', 'working' %}
  <h2 class="paper-section-heading" id="working-heading">Working papers <small>{{ working.size }}</small></h2>
  <ul class="paper-list">
    {% for paper in working %}{% include research-item.html %}{% endfor %}
  </ul>
</section>
