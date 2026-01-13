---
title: Path planning and control for soft robots
layout: page
# description: Test
permalink: /projects/trunk-project/

---

> 🔗 **Related Publications**  
> See [Robotics Publications](/publications/#robotics-publications)

![Shape-Space Graphs](/assets/img/research/ShapeSpaceAbstract.png){:width="700"}

Soft robots, inspired by elephant trunks or octopus arms, offer extraordinary flexibility to bend, twist, and elongate in ways that rigid robots cannot. However, their motion planning remains a challenge, especially in cluttered environments with obstacles, due to their highly nonlinear and infinite-dimensional kinematics. 

In my most recent work, I presented a graph-based path planning tool for an elephant-trunk-inspired soft robotic arm designed with three artificial muscle fibers that allow for multimodal continuous deformation through contraction.
The paths are directly planned in workspace, or more appropriately, *shape space* (S-space). Our method integrates a biomechanically exact forward kinematics model of a soft robotic arm with a precomputed shape library and a k-nearest neighbor graph that guarantees that all nodes correspond to physically valid shapes, enabling multi- objective planning at high speed. By using signed distance fields (SDFs), clearance is precomputed and infeasible nodes are pruned before search, avoiding expensive collision checks during runtime. This combination of exact modeling and offline graph construction allows us to eliminate dependence on inverse kinematics during online planning and generate efficient and realistic paths.

[📄 Preprint](https://arxiv.org/abs/2510.03547)


---

_Last updated: October 2025_