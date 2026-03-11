---
layout: single
title: "Academic"
permalink: /academic/
author_profile: true
---

{% include base_path %}

<div class="hb-page">
  <section class="hb-section">
    <h2>Research Interests</h2>
    <p>Optimization under uncertainty, stochastic mixed-integer programming, decomposition methods, and AI-based algorithm design for power system applications.</p>
  </section>

  <section class="hb-section">
    <h2>Publications</h2>
    <p class="hb-note">Selected publications are listed below in the same format as the original publications page.</p>
    {% for post in site.publications reversed %}
      {% include archive-single.html %}
    {% endfor %}
  </section>

  <section class="hb-section">
    <h2>Working Papers</h2>
    <ol>
      <li>H-B. Yang, L. Yang, J. Pan, Y. Wang. "Reinforcement Learning for Branch-and-Cutting-Plane-Tree in Mixed-Integer Programming." Submitted.</li>
      <li>H-B. Yang, H. Yang. "Globally Converging Algorithm for Multistage Stochastic Mixed-Integer Programs via Enhanced Lagrangian Cuts." Submitted to <em>Operations Research</em>. <a href="https://optimization-online.org/?p=29960">[Optimization-Online]</a></li>
      <li>Y. Zhou, H-B. Yang, and T. Morstyn. "Faster Inner Convex Approximation to Wasserstein Joint Chance Constrained Power System Dispatch." Submitted to <em>IEEE Transactions on Power Systems</em>. <a href="https://arxiv.org/abs/2506.18806">[arXiv]</a></li>
      <li>H-B. Yang, H. Yang. "Disjunctive Benders Cuts in Multistage Stochastic Mixed-Integer Programming." Submitted to <em>Operations Research</em>.</li>
      <li>H-B. Yang, G. Lyu. "Distribution-free model-agnostic uncertainty quantification calibration via nonparametric methods."</li>
      <li>Z. Cao, H-B. Yang, Z. Wang. "Data-Driven Optimization with (Robust) Stochastic Dominance Constraints."</li>
    </ol>
  </section>

  <section class="hb-section">
    <h2>Invited Talks</h2>
    <ol>
      <li>"Multi-period Power System Risk Minimization under Wildfire Disruptions": INFORMS Annual Meeting (Online, 2022); IEEE Student Association at CUHKSZ (Shenzhen, 2023).</li>
      <li>"Enhancement Techniques for Lagrangian Cut": Alibaba DAMO Academy (Hangzhou, 2022); International Conference on Stochastic Programming (Davis, 2023).</li>
      <li>"Multistage Stochastic Program for Mitigating Power System Risks under Wildfire Disruptions": INFORMS Annual Meeting (Phoenix, 2023, Session Chair); PSCC 2024 (Paris, 2024); INFORMS Annual Meeting (Seattle, 2024).</li>
      <li>"Efficient Cutting-Plane Methods for Multistage Stochastic Mixed-Integer Programming": ISMP 2024 (Montreal, 2024); ORSC Annual Conference (Beijing, 2024); International Conference on Stochastic Programming (Paris, 2025); The 2nd Management Forum (Xi'an, 2025).</li>
      <li>"Globally Converging Algorithm for Multistage Stochastic Mixed-Integer Programs": INFORMS Annual Meeting (Seattle, 2024, Session Chair); Global Forum for Young Mathematicians (Shenzhen, 2025).</li>
    </ol>
  </section>

  <section class="hb-section">
    <h2>Academic Services</h2>
    <ul>
      <li>Session Chair: INFORMS Annual Meeting (2023, 2024)</li>
      <li>Reviewer: Power Systems Computation Conference (PSCC)</li>
      <li>Reviewer: IEEE Transactions on Energy Markets, Policy, and Regulation</li>
      <li>Reviewer: Automatica</li>
      <li>Reviewer: Electric Power Systems Research</li>
    </ul>
  </section>

  <section class="hb-section">
    <h2>Awards</h2>
    <ul>
      <li>Duan Yongping Travel Award for Outstanding Research, CUHKSZ (2023)</li>
      <li>Award for Outstanding Graduates, SUSTech (2020)</li>
      <li>Scholarship for Outstanding Students, SUSTech (2017, 2018)</li>
    </ul>
  </section>
</div>
