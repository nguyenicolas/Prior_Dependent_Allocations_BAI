# Prior Dependent Allocations Bayesian BAI
Code and numerical experiments for the paper [Prior-Dependent Allocations for Bayesian Fixed-Budget Best-Arm Identification in Structured Bandits](https://arxiv.org/pdf/2402.05878) (AISTATS 2025).

Nicolas Nguyen, Imad Aouali, András György, Claire Vernade.


## Abstract
We study the problem of Bayesian fixed-budget best-arm identification (BAI) in structured bandits. We propose an algorithm that uses fixed allocations based on the prior information and the structure of the environment. We provide theoretical bounds on its performance across diverse models, including the first prior-dependent upper bounds for linear and hierarchical BAI. Our key contribution lies in introducing novel proof techniques that yield tighter bounds for multi-armed BAI compared to existing approaches. Our work provides new insights into Bayesian fixed-budget BAI in structured bandits, and extensive experiments demonstrate the consistent and robust performance of our method in practice across various settings. 

![Comparison](error_bounds.pdf)

## Repository Structure
This repository is structured as follows
- `MAB.ipynb`
experiments on synthetic multi-armed bandit problems.
- `linear.ipynb`
experiments on synthetic linear bandit problems.
- `hierarchical.ipynb`
experiments on synthetic hierarchical bandit problems.
- `movieles.ipynb`
experiments on movielens data.

## Contact
If any question contact nguyennicolasviet@gmail.com.
