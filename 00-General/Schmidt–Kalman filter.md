---
title: "Schmidt–Kalman filter"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Schmidt–Kalman_filter"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Schmidt–Kalman filter

The Schmidt–Kalman Filter is a modification of the Kalman filter for reducing the dimensionality of the state estimate, while still considering the effects of the additional state in the calculation of the covariance matrix and the Kalman gains. A common application is to account for the effects of nuisance parameters such as sensor biases without increasing the dimensionality of the state estimate. This ensures that the covariance matrix will accurately represent the distribution of the errors.
The primary advantage of utilizing the Schmidt–Kalman filter instead of increasing the dimensionality of the state space is the reduction in computational complexity. This can enable the use of filtering in real-time systems. Another usage of Schmidt–Kalman is when residual biases are unobservable; that is, the effect of the bias cannot be separated out from the measurement. In this case, Schmidt–Kalman is a robust way to not try and estimate the value of the bias, but only keep track of the effect of the bias on the true error distribution.
For use in non-linear systems, the observation and state transition models may be linearized around the current mean and covariance estimate in a method analogous to the extended Kalman filter.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schmidt–Kalman_filter