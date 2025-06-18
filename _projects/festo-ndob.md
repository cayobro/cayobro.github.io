---
title: Nonlinear Disturbance Observers for Robotic Continuum Manipulators
layout: page
# description: Test
permalink: /projects/festo-ndob/

---
I worked with **[Festo's Bionic soft arm](https://www.festo.com/us/en/e/about-festo/research-and-development/bionic-learning-network/bionic-grippers-and-soft-robots-id_33288/)** as a graduate research assistant at University of Stuttgart (2019-2020).

> 🔗 **Related Publications**  
> See [Robotics Publications](/publications/#robotics-publications)

![Festo BSA](/assets/img/research/festo-bsa.jpg){:width="500"}

A safe collaborative work environment is enabled by so-called soft robots, which constitute a human-friendly alternative to classical rigid industrial robots. However, modeling soft robots proves difficult and results in a lack of accuracy for control tasks.
I introduced the concept of **disturbance observer-based control** for Festo's Bionic Soft arm, a quasi-continuum manipulators with pneumatic bellows. In doing so, unknown model errors are considered as disturbances and estimated by an observer. This estimate is used to actively reject the perturbation. 
All implemented observer concepts (nonlinear observers, EKFs) combined with a PD control show superior performance compared to an existing benchmark concept based on PID-like control. Thanks to the modularity of this approach, disturbance observers are a **simple, yet powerful addition to any control concept**.

[📄 Key publication](https://doi.org/10.1016/j.mechatronics.2021.102518)

![NDOB Concept](/assets/img/research/ndob.jpg){:width="500"}

During this time, I also contributed to other research that dealt with:
- Hybrid force/position control [📄](https://doi.org/10.1515/auto-2020-0053).
- One-Shot kinesthetic programming by demonstration [📄](https://doi.org/10.1016/j.mechatronics.2020.102418).

---

_Last updated: June 2025_


