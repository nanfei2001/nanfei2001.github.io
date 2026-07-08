---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

Sequential decision-making in cyber-physical and networked systems raises three recurring technical issues: safety, information constraints, and economic incentives.

Safe learning and online control
------
Learning-based controllers must explore uncertain dynamics while operating under constraints. In safety-critical systems, constraint violations during learning are part of the problem, not an acceptable transient cost.

Recent work studies constrained linear quadratic regulators with unknown dynamics, unbounded disturbances, and state-input safety constraints. The goal is to obtain near-optimal regret while maintaining chance-constraint satisfaction.

Related papers:
- Near-Optimal Regret for the Safe Learning-based Control of the Constrained Linear Quadratic Regulator
- Online Nonstochastic Control with Convex Safety Constraints

Strategic querying for stochastic optimization
------
Stochastic gradient methods usually assume that gradient samples are queried uniformly or freely. This assumption is restrictive when query access is costly, limited, or tied to strategic participants.

This line of work studies how query rules affect transient convergence, final optimization error, and participant-side utility. The technical question is how to allocate a limited query budget without losing the convergence guarantees that make stochastic gradient methods useful.

Related papers:
- Strategic Querying for Stochastic Gradient Methods
- Stochastic Gradient Descent with Strategic Querying

Pricing and market design for EV charging
------
Electric-vehicle charging combines continuous charging schedules with binary station-access decisions. This mixed continuous-discrete structure makes traditional marginal pricing difficult.

This work uses convex and copositive duality to construct prices for charging and station access, capturing EVSE congestion while preserving revenue adequacy and user incentive guarantees.

Related paper:
- Pricing Electric Vehicle Charging and Station Access via Copositive Duality

Representative Papers
------
{% include publications-list.html limit=5 %}
