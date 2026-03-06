---
title: Soft robots
layout: page
# description: Test
permalink: /projects/trunk-project/

---

> 🔗 **Related Publications**  
> See [Robotics Publications](/publications/#robotics-publications)

Soft robots, inspired by elephant trunks or octopus arms, offer extraordinary flexibility to bend, twist, and elongate in ways that rigid robots cannot. With their their highly nonlinear and infinite-dimensional dynamics, conventional (rigid) robotics methods that usually only focus on end-effector position, quickly encounter limits.

In this project, I investigated how we can account for the entire robot shape during control, not just the end-effector.

### Infinite-Dimensional Closed-Loop Inverse Kinematics for Soft Robots

![CLIK](/assets/img/research/clik-abstract.png){:width="700"}

In robotics, closed-loop inverse kinematics are an efficient tool to position the end-effector of rigid manipulators in space.
For soft robots in infinite-dimensional shape spaces, we encouter limits both in the mathematical theory behind but also the limited usefulness when not being able to reason about the entire robot shape.

In the paper, we extend CLIK to infinite-dimensional shape spaces by composing an actuation-to-shape map with a shape-to-task map, deriving the differential end-to-end kinematics via an infinite-dimensional chain rule. Since this actuation-to-shape mapping is rarely available in closed form, we propose to learn it using differentiable neural operator networks -- et voilà, CLIK for soft robots and reasoning about entire shapes rather than just end-effectors.

[📄 Preprint](https://arxiv.org/abs/2602.18655)

[🖥️ GitHub](https://github.com/cayobro/soft-robot-CLIK-via-neural-operators)

### Shape-Space Graphs for Fast and Collision-Free Path Planning

![Shape-Space Graphs](/assets/img/research/ShapeSpaceAbstract.png){:width="700"}

Here, I present a graph-based path planning tool for an elephant-trunk-inspired soft robotic arm designed with three artificial muscle fibers that allow for multimodal continuous deformation through contraction.
The paths are directly planned in workspace, or more appropriately, *shape space* (S-space). Our method integrates a biomechanically exact forward kinematics model of a soft robotic arm with a precomputed shape library and a k-nearest neighbor graph that guarantees that all nodes correspond to physically valid shapes, enabling multi- objective planning at high speed. By using signed distance fields (SDFs), clearance is precomputed and infeasible nodes are pruned before search, avoiding expensive collision checks during runtime. This combination of exact modeling and offline graph construction allows us to eliminate dependence on inverse kinematics during online planning and generate efficient and realistic paths.

[📄 Preprint](https://arxiv.org/abs/2510.03547)

[🖥️ GitHub](https://github.com/cayobro/shape-space-graphs)

---

_Last updated: March 2026_