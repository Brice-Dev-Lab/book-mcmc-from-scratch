# MCMC from Scratch

![Python](https://img.shields.io/badge/python-3.11+-blue.svg)
![Status](https://img.shields.io/badge/status-in%20progress-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Focus](https://img.shields.io/badge/focus-MCMC%20%7C%20Bayesian%20Inference%20%7C%20Monte%20Carlo-informational)
![Math](https://img.shields.io/badge/math-probability%20%26%20statistics-purple)
![Built With](https://img.shields.io/badge/built%20with-NumPy%20%7C%20SciPy%20%7C%20Matplotlib-darkgreen)
![Domain](https://img.shields.io/badge/domain-computational%20statistics-critical)
![Difficulty](https://img.shields.io/badge/level-intermediate%20to%20advanced-red)

A working study repository for learning and implementing Markov Chain Monte Carlo (MCMC) methods using the book:

> *MCMC from Scratch: A Practical Introduction to Markov Chain Monte Carlo*  
> by Masanori Hanada and So Matsuura  
> Springer, 2022.

This repository focuses on developing an intuitive and practical understanding of Monte Carlo simulation, probabilistic sampling, and Markov Chain Monte Carlo methods through mathematical derivations, Python implementations, experimentation, and visualization.

The goal is not simply to “run an algorithm,” but to understand:
- why MCMC works,
- when it fails,
- how convergence behaves,
- how sampling quality is evaluated,
- and how these methods connect to machine learning, Bayesian inference, physics, quantitative finance, and reliability engineering.

Because eventually every sufficiently advanced statistical problem becomes:
> “We cannot solve this analytically anymore.”

At which point humanity starts throwing probability distributions at the wall until the posterior converges.

---

# Objectives

This repository is intended to serve as:

- A structured learning environment for MCMC fundamentals
- A reference for probabilistic simulation techniques
- A computational mathematics and statistics portfolio project
- A foundation for future work in:
  - Bayesian statistics
  - Quantitative finance
  - Machine learning
  - Reliability engineering
  - Scientific computing
  - Infrastructure risk modeling
  - Monte Carlo simulation systems

---

# Topics Covered

The repository follows the progression of the book while expanding concepts through additional experimentation and implementation.

## Core Topics

- Monte Carlo simulation
- Random number generation
- Probability distributions
- Markov chains
- Detailed balance
- Irreducibility and ergodicity
- Burn-in / thermalization
- Autocorrelation
- Acceptance ratios
- Sampling efficiency
- Convergence behavior

---

# MCMC Algorithms

The repository includes implementations and experimentation with:

- Metropolis Algorithm
- Metropolis-Hastings
- Gibbs Sampling
- Hamiltonian Monte Carlo (HMC)
- Hybrid approaches
- Multivariate sampling methods

Additional algorithms and variations may be explored over time.

---

# Mathematical Focus

This project emphasizes understanding the mathematics behind the algorithms rather than treating MCMC as a black-box library tool.

Areas of focus include:

- Probability theory
- Numerical integration
- Statistical estimation
- Linear algebra
- Random processes
- Optimization concepts
- Stochastic systems
- Sampling theory

---

# Visualization and Analysis

The repository will include visual exploration of:
- probability distributions,
- random walks,
- convergence behavior,
- chain mixing,
- autocorrelation,
- sampling efficiency,
- and multidimensional sampling spaces.

Visualization is critical because MCMC often appears to work while quietly producing misleading results. Statistics has a long and proud history of confidently incorrect conclusions supported by beautiful graphs.

---

# Learning Philosophy

This repository is intentionally implementation-focused.

The objective is to:
- derive concepts,
- build algorithms from scratch,
- test assumptions,
- inspect failures,
- and understand computational tradeoffs.

High-level libraries are useful, but implementing algorithms manually develops a deeper understanding of:
- stochastic systems,
- probabilistic reasoning,
- numerical stability,
- and computational statistics.

---

# Architecture and Repository Organization

Repository organization, development standards, and project layout are documented in:

`docs/01_architecture/01_structure.md`

This document serves as the authoritative reference for repository structure and architectural conventions.

---

# Technologies

Primary technologies and libraries used throughout the repository may include:

- Python
- NumPy
- SciPy
- pandas
- Matplotlib
- Jupyter Notebooks
- SymPy
- seaborn (select visualizations)
- arviz (later-stage diagnostics)

Additional tooling may be introduced as the project evolves.

---

# Practical Applications

MCMC methods are widely used in:
- Bayesian inference
- Quantitative finance
- Machine learning
- Physics simulations
- Reliability engineering
- Computational biology
- Econometrics
- Scientific computing

The long-term goal of this repository is to bridge theoretical understanding with practical applications in:
- infrastructure analytics,
- risk modeling,
- predictive systems,
- and probabilistic engineering workflows.

---

# Reference Text

## Primary Text

*MCMC from Scratch: A Practical Introduction to Markov Chain Monte Carlo*  
Masanori Hanada & So Matsuura  
Springer Nature Singapore, 2022.

The text introduces MCMC concepts progressively, covering:
- Monte Carlo methods,
- Markov chains,
- Metropolis algorithms,
- Gibbs sampling,
- Hamiltonian Monte Carlo,
- and practical implementation considerations.

---

# Notes

This repository is educational in nature and prioritizes:
- conceptual clarity,
- reproducibility,
- experimentation,
- and professional documentation practices.

Some implementations may intentionally favor readability and learning value over maximum computational performance.

Because understanding why a simulation behaves badly is usually more valuable than generating incorrect results at scale. Modern computing occasionally forgets this.