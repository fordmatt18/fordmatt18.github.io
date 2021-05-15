---
layout: default
title: Projects
---

# Projects (all works in progress)
-----------------

### SimOpt: 
I have recently started contributing to SimOpt - a library for benchmarking simulation optimization algorithms with finite simulation budgets. Here is the [Read the Docs site](https://simopt.readthedocs.io/) that I set up and the [GitHub repo](https://github.com/simopt-admin/simopt/tree/python_dev/simopt).

### End-to-end Stochastic Contextual Linear Optimization by Retargeting the Prediction Problem: 
This project explores different methods to predict the cost vectors, from some observed context, of a downstream linear decision making task.  We specifically explore heuristic methods, inspired by distributionally robust optimization, for reweighting the squared error loss to train our prediction model. The hope is to make more accurate predictions on the decision making problems which are most sensitive to our predictions, thus giving better performance on the ultimate decision making task. I must give my brilliant colleague [Andrew Bennett](https://awbennett.net/) a shoutout for contributing most of the ideas and work to this project. Here is the [GitHub repo](https://github.com/fordmatt18/6751-project).

### Reinforcement Learning for an Inventory Model:
This project trains reinforcement learning policies on an inventory model with positive order lead times and a lost sales penalty. For this inventory system, [Xin & Goldberg](https://arxiv.org/abs/1409.1499) have shown that a constant order policy is asymptotically optimal as the lead time increases. They have also derived bounds on the competitive ratio of the optimal constant order policy compared to the optimal unrestricted policy. Our goal is to explore how tight these bounds may be by comparing the ratio of the optimal constant order policy to policies learned by reinforcement learning. I worked with [Anna Poulton](https://www.cam.cornell.edu/research/grad-students/anna-poulton) on this project. Here is the [GitHub repo](https://github.com/fordmatt18/gym-inventory).