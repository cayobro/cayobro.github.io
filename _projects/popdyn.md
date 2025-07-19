---
title: Controlling multi-species population dynamics
layout: page
keywords: [Carina Veil, PDE, Control, Population Dynamics, Researcher]
# description: Test
permalink: /projects/popdyn/

---

- Funding: partially funded by German Research Foundation, grant SA 847/22-2.
- PIs and collaborators: Oliver Sawodny (University of Stuttgart), Miroslav Krstić (UC San Diego).

> 🔗 **Related Publications**  
> See [Control Theory Publications](/publications/#control-theory-publications)

Populations (in ecology, epidemics, biotechnology, economics, social processes) do not only interact over time but also age over time. It is therefore common to model them as **age-structured partial differential equations**, where age is the ‘space variable’. Since the models also involve integrals over age, both in the birth process and in the interaction among species, they are in fact integro-partial differential equations (IPDEs) with positive states and inputs, turning them into an **extremely challenging control problem**.

<!-- The interest in extending the foundational design and analysis from single-species to multi-species dynamics goes in many direction, as they open exciting possibilities for future research directions, especially in epidemiology or for analyzing ecosystem stability and food webs, involving multiple predators and preys, or even superpredators or infected preys. -->

Our works revolve around the fact that the considered familiy of IPDE systems can be transformed into a system of two coupled ordinary differential equations (ODE) and two autonomous, exponentially stable integral delay equations (IDE).

## Predator-Prey Dynamics
![Predator-Prey Dynamics](/assets/img/research/predatorprey.png){:width="500"}

With a modified **Volterra-like control Lyapunov function**, 
- We design a simple feedback which employs possibly negative harvesting for global stabilization of the ODE model, while guaranteeing regional regulation with positive harvesting.
- Extending this to a more sophisticated, restrained controller we achieve regulation for the ODE model globally, with positive harvesting. 
- For the full IPDE model, with the IDE dynamics acting as large disturbances, for both the simple and saturated feedback laws we provide explicit estimates of the regions of attraction.

[📄 Key publication](https://arxiv.org/abs/2410.06823)

## Predator-Predator Dynamics
![Predator-Prey Dynamics](/assets/img/research/PredatorPredator.png){:width="500"}

Using **backstepping**,
- The ODEs are globally stabilized.
- An estimate of the region of attraction of the asymptotically stabilized equilibrium of the full IPDE system is provided, under a positivity restriction on control.


📄 As of June 2025, results have just been submitted to *automatica*, and we are waiting for a decision notification from CDC 2025.

---

_Last updated: June 2025_
