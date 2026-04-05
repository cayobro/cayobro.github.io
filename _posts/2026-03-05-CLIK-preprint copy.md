---
layout: post
title: "[preprint] Infinite-Dimensional Closed-Loop Inverse Kinematics via Neural Operators"
date: 2026-03-05
---

In robotics, 𝘤𝘭𝘰𝘴𝘦𝘥-𝘭𝘰𝘰𝘱 𝘪𝘯𝘷𝘦𝘳𝘴𝘦 𝘬𝘪𝘯𝘦𝘮𝘢𝘵𝘪𝘤𝘴 are an efficient tool to position the end-effector of rigid manipulators in space - but they quickly encounter limits with soft robots, where not all configurations are attainable through control action. And also, what if we want to reason about the 𝘦𝘯𝘵𝘪𝘳𝘦 𝘴𝘰𝘧𝘵 𝘳𝘰𝘣𝘰𝘵 𝘴𝘩𝘢𝘱𝘦 while solving tasks, not just the end-effector? 🐘 🐙 

This wraps up an amazing postdoc year at Stanford University in Ellen Kuhl's Living Matter Lab, and a fantastic collaboration with Cosimo Della Santina (that came with a nice visit to beautiful TU Delft last fall 🇳🇱)

In the paper, we extend CLIK to infinite-dimensional shape spaces by composing an actuation-to-shape map with a shape-to-task map, deriving the differential end-to-end kinematics via an infinite-dimensional chain rule. Since this actuation-to-shape mapping is rarely available in closed form, we propose to learn it using differentiable 𝘯𝘦𝘶𝘳𝘢𝘭 𝘰𝘱𝘦𝘳𝘢𝘵𝘰𝘳 𝘯𝘦𝘵𝘸𝘰𝘳𝘬𝘴 - et voilà, CLIK for soft robots and reasoning about entire shapes rather than just end-effectors. 🥳create a patient-specific vascular fingerprint that we can use for navigation, basically like a roadmap helping surgeons find their way back to important spots.

📃 Link: [arXiv](https://arxiv.org/abs/2602.18655)

ℹ️ More about this project: [Soft Robots](/projects/trunk-project/)


![CLIK](/assets/img/news/clik-paper.png){:width="600"}