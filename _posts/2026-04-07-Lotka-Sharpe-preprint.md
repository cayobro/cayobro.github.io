---
layout: post
title: "[preprint] Lotka-Sharpe Neural Operator for Control of Population PDEs"
date: 2026-04-07
---

Populations (in ecology, epidemics, biotechnology, economics, social processes) do not only interact over time but also age over time. It is therefore common to model them as **age-structured partial differential equations**, where age is the ‘space variable’. Since the models also involve integrals over age, both in the birth process and in the interaction among species, they are in fact integro-partial differential equations (IPDEs) with positive states and inputs, turning them into an **extremely challenging control problem**.

Even after developing suitable control strategies [1](https://ieeexplore.ieee.org/abstract/document/11080060), [2](https://arxiv.org/abs/2507.23013), one challenge remains: the scalar ζ, defined implicitly by the Lotka-Sharpe nonlinear integral condition, as a mapping from age-dependent fertility and mortality rates to ζ. To solve this challenge with operator learning, we first prove that the Lotka-Sharpe operator is Lipschitz continuous, guaranteeing the existence of arbitrarily accurate neural operator approximations over a compact set of fertility and mortality functions. We then show that the resulting approximate feedback law preserves semi-global practical asymptotic stability under propagation of the operator approximation error through various other nonlinear operators, all the way through to the control input.

💡 Easy version: [Gist](https://gist.science/paper/2604.03892#technical)

📃 Link: [arXiv](https://arxiv.org/abs/2604.03892)

ℹ️ More about this project: [Population Dynamics](/projects/popdyn/)


<!-- ![CLIK](/assets/img/news/clik-paper.png){:width="600"} -->