---
layout: post
usemath: true
title: "Generating Financial Markets"
subtitle: 
categories:
- Functional Data
tags:
- finance
- generator
- functional data
- time-series
- metric
---

<h3> Classical Modelling for numerical data simulation in finance </h3>

<h4> 1. Classical stochastic market models (eg. Heston, SABR) and autoregressive models.</h4>
- advantages : tractability and more straightforward suitability to currently prevalent risk-management frameworks.
- disadvantages : relative inflexibility

<h5>Stochastic Volatility Model</h5>
stochastic volatility model is a financial model that assumes the volatility of the option price is a random variable itself. This is the key difference with the Black-Scholes Model.

<h6> (i) Heston Model </h6>

$$ dS_{t} = rS_{t}dt + \sqrt{V_{t}} S_{t} dW_{1t} $$
$$ dV_{t} = k(\theta - V_{t})dt + \delta \sqrt{V_{t}}dW_{2t}$$
where,
$S_{t}$ is stock price at time t.
$r =$ risk-free interest rate - theoretical risk-free interest rate
$\sqrt{V_{t}}$ is the volatality (standard deviation) of the asset price
$\detla$ is the volatality of $\sqrt{V_{t}}$
$\theta$ is the long-term price variance
$k$ is rate of reversion to $\theta$
$dt$ is indefininte small time n=increment
$W_{1t}$ is the Browninan motion of asset price
$W_{2t}$ is the Browninan motion of asset's price volatility


-- Properties of Heston Model --
- It factors in a possible correlation between a stock's price and its volatility.
- It conveys volatility as reverting to the mean.
- It gives a closed-form solution, meaning that the answer is derived from an accepted set of mathematical operations.
- It does not require that stock prices follow a lognormal probability distribution.

<h7> (ii) SABR Model </h7>




the Chen model, and the GARCH model.


<h4> 2. Data-Driven Simulation : GAN, VAE </h4>

<h3> Challenges of Financial Time-series Simulation
