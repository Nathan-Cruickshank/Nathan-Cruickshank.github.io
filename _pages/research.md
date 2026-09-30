---
layout: single
title: "Research & Methods"
permalink: /research/
---

My research bridges the gap between theoretical physics and precision observational data. I explore the underlying nature of the dark sector, modifying numerical solvers and applying advanced statistical methods to test these theories against next-generation cosmological surveys.

## The Physics of My Research

<div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: center;" markdown="1">

<div style="flex: 1; min-width: 300px;" markdown="1">
* **Dark Matter & Dark Energy:** The Universe is dominated by two unknown components. Dark matter provides the invisible gravitational framework that binds together galaxies and galaxy clusters, while dark energy is the mysterious force driving the accelerated expansion of the cosmos.
* **Large-Scale Structure:** This refers to the vast cosmic web of galaxies and dark matter. By observing how this structure evolves over time, we can test our theoretical models. Recent measurements show that the Universe is slightly less clustered than standard models predict (the <i>S<sub>8</sub></i> tension).
* **Interacting Models:** Interactions between particles can result in the exchange of energy and momentum or the production of new particles. It is possible that dark matter and dark energy interact through one of these channels, with pure momentum exchange being proposed as a way to slow the growth of large-scale structure by exerting a friction-like drag on dark matter.
</div>

<div style="flex: 0 0 350px; margin: auto; text-align: center;">
  <img src="/images/LSS_cosmic_web.jpg" alt="Simulation of the cosmic web large-scale structure" style="width: 100%; border-radius: 5px;">
  <p style="font-size: 0.85em; color: #aaaaaa; margin-top: 8px;"><i>Image credit: Boylan-Kolchin et al. (2009)</i></p>
</div>

</div>

## Technical Expertise & Methods
* **Simulations & Solvers:** I modify highly specialised Einstein-Boltzmann solvers, primarily working in C with **CLASS**, to implement new dark energy and redshift-binned interaction models. I use this code to accurately model complex dark sector fluid dynamics and the impact on the growth of linear matter perturbations.
* **Fisher Forecasting:** I build Python-based Fisher forecasting pipelines that utilise theoretical linear matter power spectra and growth rates as mock data to evaluate the constraining power of Stage IV cosmological survey observations.
* **Statistical Inference:** I write custom Markov Chain Monte Carlo (MCMC) likelihoods for use with **MontePython** to rigorously explore parameter spaces and test theoretical models against synthetic survey data.
