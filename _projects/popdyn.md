---
title: PDE control for population dynamics
layout: page
keywords: [Carina Veil, PDE, Control, Population Dynamics, Researcher, Krstic]
# description: Test
permalink: /projects/popdyn/

---

*This research is related to my time as a Postdoc with Miroslav Krstić at University of California San Diego, but still spans to this day.*

---

> 🔗 **Related Publications**  
> See [Control Theory Publications](/publications/#control-theory-publications)

Populations (in ecology, epidemics, biotechnology, economics, social processes) do not only interact over time but also age over time. It is therefore common to model them as **age-structured partial differential equations**, where age is the ‘space variable’. Since the models also involve integrals over age, both in the birth process and in the interaction among species, they are in fact integro-partial differential equations (IPDEs) with positive states and inputs, turning them into an **extremely challenging control problem**.

<!-- The interest in extending the foundational design and analysis from single-species to multi-species dynamics goes in many direction, as they open exciting possibilities for future research directions, especially in epidemiology or for analyzing ecosystem stability and food webs, involving multiple predators and preys, or even superpredators or infected preys. -->


![Population Dynamics](/assets/img/research/popdyn-overview.png){:width="800"}

## Control Lyapunov functions for population dynamics with two species
Our works revolve around the fact that the considered family of IPDE systems can be transformed into a system of two coupled ordinary differential equations (ODE) and two autonomous, exponentially stable integral delay equations (IDE). While predator-prey systems can only be stabilized through *simultaneous harvesting* (removal) of both species, predator-predator systems require *asymetric harvesting* of one species.

For **predator-prey** scenarios we use a **Volterra-like control Lyapunov function**:
- We design a simple feedback which employs possibly negative harvesting for global stabilization of the ODE model, while guaranteeing regional regulation with positive harvesting.
- Extending this to a more sophisticated, restrained controller we achieve regulation for the ODE model globally, with positive harvesting. 
- For the full IPDE model, with the IDE dynamics acting as large disturbances, for both the simple and saturated feedback laws we provide explicit estimates of the regions of attraction.   

For **predator-predator** scenarios under asymetric harvesting, we further need to apply **backstepping**. Then:
- The ODEs are globally stabilized.
- An estimate of the region of attraction of the asymptotically stabilized equilibrium of the full IPDE system is provided, under a positivity restriction on control.

[📄 Predator-prey publication](https://ieeexplore.ieee.org/abstract/document/11080060) (also on [arxiv](https://arxiv.org/abs/2410.06823)) and 
[📄 Predator-predator publication](https://arxiv.org/abs/2507.23013)


## Lotka-Sharpe neural operator for control
A key challenge in feedback design for these systems is the scalar ζ, defined implicitly by the Lotka-Sharpe nonlinear integral condition, as a mapping from fertility and mortality rates to ζ. To solve this challenge with operator learning, we first prove that the Lotka-Sharpe operator is Lipschitz continuous, guaranteeing the existence of arbitrarily accurate neural operator approximations over a compact set of fertility and mortality functions. We then show that the resulting approximate feedback law preserves semi-global practical asymptotic stability under propagation of the operator approximation error through various other nonlinear operators, all the way through to the control input.

[📄 Key publication](https://arxiv.org/abs/2604.03892)
[🖥️ GitHub](https://github.com/lukebhan/Lotka-SharpeNeuralOperatorsforControlofPopulationPDEs)  
[💡 Gist](https://gist.science/paper/2604.03892#technical)

---

_Last updated: April 2026_
