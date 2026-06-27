---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

Current Ph.D. Work
======
I work on online decision-making problems in control, optimization, and energy systems. A recurring question in my research is how to design algorithms that learn or optimize over time while respecting real constraints: safety constraints in dynamical systems, query constraints in optimization, and incentive constraints in energy markets.

Research Threads
======

Safe online control
------
I study online control algorithms that can handle adversarial costs and disturbances while maintaining safety constraints throughout the trajectory. This line of work is motivated by safety-critical cyber-physical systems, where violating a state or input constraint during learning is not acceptable.

Strategic querying for optimization
------
In stochastic optimization, uniformly sampling gradients can waste queries when different users or data sources have different value at different stages of training. My work studies strategic querying rules that use a limited query budget more efficiently while preserving theoretical guarantees.

Safe adaptive LQR
------
I am also interested in adaptive control with unknown dynamics and per-step constraints. Recent work studies how to obtain near-optimal regret while satisfying chance constraints in constrained linear quadratic regulator problems.

EV charging, pricing, and discrete access
------
Electric-vehicle charging systems combine continuous charging decisions with discrete station-access decisions. I study pricing mechanisms that can handle this nonconvex structure and still provide economically meaningful incentives.

Representative Papers
======
{% include publications-list.html limit=4 %}
