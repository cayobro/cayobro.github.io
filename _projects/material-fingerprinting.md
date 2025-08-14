---
title: Material Fingerprinting
layout: page
# description: Test
permalink: /projects/material-fingerprinting/

---
- Funding: European Research Council (ERC) Grant 101141626 DISCOVER.
- PIs and collaborators: Ellen Kuhl (Stanford University), Moritz Flaschel, Denisa Martonová (FAU Erlangen).

Material model discovery without solving an optimization problem? Yes!

The key idea: every material exhibits a unique response in an experiment, which can be interpreted as its fingerprint. If we build a database of these fingerprints linked to their corresponding mechanical models during an offline phase, we can then rapidly identify the model of a new, unseen material during an online phase using a pattern recognition algorithm. 🕵‍♀️🔍 

* fast model discovery
* no optimization problem
* no risk of getting stuck in local optima
* physically admissible and interpretable material models

In our [preprint](https://arxiv.org/abs/2508.07831), we demonstrate this concept for both homogeneous (supervised) and heterogeneous (unsupervised) experiments. The code is available on [github](https://github.com/Material-Fingerprinting/material-fingerprinting-hyperelasticity).

![Material Fingerprinting](/assets/img/research/material-fingerprinting.png){:width="500"}


---

_Last updated: August 2025_