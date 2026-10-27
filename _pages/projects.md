---
layout: single
title: "Projects"
permalink: /projects/
description: "Code and research projects by Clemente Romano."
author_profile: true
---

## Signature-based optimal execution

**Signature methods · Optimal execution · Python**

This project studies optimal trade execution with trading speeds expressed as linear functionals of the observed price path's signature. A custom symbolic algebra layer uses shuffle products and tensor concatenation to assemble quadratic execution objectives.

Validation includes a Brownian optimal-inventory benchmark, a liquidation problem with a known closed form, and geometric Brownian motion experiments. The implementation checks objective curvature before accepting a stationary point as an optimum.

![Expected inventory over time: signature control closely follows the classical Brownian optimal-execution solution.]({{ '/images/signature-execution-brownian.png' | relative_url }})

*Brownian benchmark: expected inventory from the signature-based control compared with the classical solution for the notebook's example.*

[View the repository](https://github.com/clementeromano/signature-optimal-execution)

---

## Kalman filtering with signatures

**Stochastic filtering · Signature methods · Jupyter Notebook**

This project numerically reproduces the recovery of the continuous-time Kalman–Bucy filter using linear signature regression. The repository contains the implementation and notebooks for exploring the method.

[View code and notebooks](https://github.com/clementeromano/kalman-filter-with-signatures)

---

## Polymarket–Kalshi arbitrage research

**Prediction markets · ATP tennis · Python**

This project collects ATP tennis data and investigates cross-exchange arbitrage using Polymarket and Kalshi.

[View the repository](https://github.com/clementeromano/Polymarket-Kalshi_arbitrage)

---

[More on GitHub](https://github.com/clementeromano)
