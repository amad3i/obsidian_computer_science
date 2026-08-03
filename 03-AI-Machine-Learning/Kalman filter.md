---
title: "Kalman filter"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Kalman_filter"
wikipedia_categories: ["Control theory", "Hungarian inventions", "Linear filters", "Markov models", "Nonlinear filters", "Robot control", "Signal estimation", "Stochastic differential equations"]
related: ["[[Switching Kalman filter]]", "[[Covariance intersection]]", "[[Moving horizon estimation]]", "[[Projection filters]]", "[[Unscented transform]]", "[[Bellman filter]]", "[[Filtering problem (stochastic processes)]]", "[[Particle filter]]", "[[Obstacle avoidance]]", "[[Underactuation]]"]
---

# Kalman filter

In statistics and control theory, Kalman filtering (also known as linear quadratic estimation) is an algorithm that uses a series of measurements observed over time, including statistical noise and other inaccuracies, to produce estimates of unknown variables that tend to be more accurate than those based on a single measurement, by estimating a joint probability distribution over the variables for each time-step. The filter is constructed as a mean squared error minimiser, but an alternative derivation of the filter is also provided showing how the filter relates to maximum likelihood statistics. The filter is named after Rudolf E. Kálmán.
Kalman filtering has numerous technological applications. A common application is for guidance, navigation, and control of vehicles, particularly aircraft, spacecraft and ships positioned dynamically. Furthermore, Kalman filtering is much applied in time series analysis tasks such as signal processing and econometrics. Kalman filtering is also important for robotic motion planning and control, and can be used for trajectory optimization. Kalman filtering also works for modeling the central nervous system's control of movement. Due to the time delay between issuing motor commands and receiving sensory feedback, the use of Kalman filters provides a realistic model for making estimates of the current state of a motor system and issuing updated commands.
The algorithm works via a two-phase process: a prediction phase and an update phase. In the prediction phase, the Kalman filter produces estimates of the current state variables, including their uncertainties. Once the outcome of the next measurement (necessarily corrupted with some error, including random noise) is observed, these estimates are updated using a weighted average, with more weight given to estimates with greater certainty. The algorithm is recursive. It can operate in real time, using only the present input measurements and the state calculated previously and its uncertainty matrix; no additional past information is required.
Optimality of Kalman filtering assumes that errors have a zero mean normal (Gaussian) distribution. In the words of Rudolf E. Kálmán, "The following assumptions are made about random processes: Physical random phenomena may be thought of as due to primary random sources exciting dynamic systems. The primary sources are assumed to be independent gaussian random processes with zero mean; the dynamic systems will be linear." Regardless of Gaussianity, however, if the process and measurement covariances are known and mean is zero, then the Kalman filter is the best possible linear estimator in the minimum mean-square-error sense, although there may be better nonlinear estimators. It is a common misconception (perpetuated in the literature) that the Kalman filter cannot be rigorously applied unless all noise processes are assumed to be Gaussian.
Extensions and generalizations of the method have also been developed, such as the extended Kalman filter and the unscented Kalman filter which work on nonlinear systems. The basis is a hidden Markov model such that the state space of the latent variables is continuous and all latent and observed variables have Gaussian distributions. Kalman filtering has been used successfully in multi-sensor fusion, and distributed sensor networks to develop distributed or consensus Kalman filtering.

## Related

- [[Switching Kalman filter]]
- [[Covariance intersection]]
- [[Moving horizon estimation]]
- [[Projection filters]]
- [[Unscented transform]]
- [[Bellman filter]]
- [[Filtering problem (stochastic processes)]]
- [[Particle filter]]
- [[Obstacle avoidance]]
- [[Underactuation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kalman_filter