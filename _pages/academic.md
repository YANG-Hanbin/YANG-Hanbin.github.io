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
    {% for post in site.publications reversed %}
      {% include archive-single.html %}
    {% endfor %}
  </section>

  <section class="hb-section">
    <h2>Working Papers</h2>
    <ol>
      <li><strong>H.-B. Yang</strong> and H. Yang. "Globally Converging Algorithm for Multistage Stochastic Mixed-Integer Programs via Enhanced Lagrangian Cuts." Major revision at <em>Operations Research</em>. <a href="https://optimization-online.org/2025/04/globally-converging-algorithm-for-multistage-stochastic-mixed-integer-programs-via-enhanced-lagrangian-cuts/">[Preprint]</a></li>
      <li>Y. Zhou, <strong>H.-B. Yang</strong>, and T. Morstyn. "Faster Inner Convex Approximation to Wasserstein Joint Chance Constrained Power System Dispatch." Submitted to <em>IEEE Transactions on Power Systems</em>. <a href="https://arxiv.org/abs/2506.18806">[Preprint]</a></li>
      <li><strong>H.-B. Yang</strong> and G. Lyu. "Locally Valid Dantzig–Wolfe Optimality Cuts for Stochastic Mixed-Integer Programs." Submitted to <em>Mathematical Programming</em>. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7126720">[Preprint]</a></li>
      <li><strong>H.-B. Yang</strong>, N. Jiang, and G. Lyu. "Contextual Distributionally Robust Chance Constraints: Exact Reformulations and Valid Inequalities." Submitted to <em>Operations Research</em>. <a href="https://arxiv.org/abs/2609.23739">[Preprint]</a></li>
      <li>Y. Zhou, <strong>H.-B. Yang</strong>, and T. Morstyn. "Finite-Sample Probabilistic Safety Certification for AI-Based Grid Operation." Submitted to <em>IEEE Transactions on Smart Grid</em>. <a href="https://arxiv.org/pdf/2609.28182">[Preprint]</a></li>
      <li>(α-β) B. Hao, C. Michini, and <u><strong>H.-B. Yang</strong><sup>⋆</sup></u>. "Upper Bounds for Symmetric Matroid Congestion Games from Exchange Flow Expansion." To be submitted to IPCO 2026.</li>
      <li>(α-β) K. Fang and <u><strong>H.-B. Yang</strong><sup>⋆</sup></u>. "Integral-Valid Cut Selection for Benders Decomposition." To be submitted to <em>INFORMS Journal on Computing</em>.</li>
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
      <li>"Locally Valid Dantzig–Wolfe Optimality Cuts for Stochastic Mixed-Integer Programs": INFORMS Annual Meeting (San Francisco, Nov. 2026); POMS-HK (Guangzhou, Jan. 2027, Session Chair).</li>
    </ol>
  </section>

  <section class="hb-section">
    <h2>Academic Services</h2>
    <ul>
      <li>Session Chair: INFORMS Annual Meeting (2023, 2024); POMS-HK 2027</li>
      <li>Reviewer: Mathematical Programming</li>
      <li>Reviewer: Nature Communications</li>
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
      <li>Outstanding Graduate Award, SUSTech (2020)</li>
      <li>Scholarship for Outstanding Students, SUSTech (2017, 2018)</li>
    </ul>
  </section>
</div>
