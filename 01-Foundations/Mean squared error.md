---
title: "Mean squared error"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Mean_squared_error"
wikipedia_categories: ["Least squares", "Loss functions", "Point estimation performance", "Statistical deviation and dispersion"]
related: ["[[Mean squared prediction error]]", "[[Common-method variance]]", "[[Hinge loss]]", "[[Huber loss]]", "[[Least-squares spectral analysis]]", "[[Loss function]]", "[[Partial least squares regression]]", "[[Propagation of uncertainty]]", "[[Regularized least squares]]", "[[Root mean square deviation of atomic positions]]"]
---

# Mean squared error

In statistics, the mean squared error (MSE) or mean squared deviation (MSD) of an estimator (of a procedure for estimating an unobserved quantity) measures the average of the squares of the errors—that is, the average squared difference between the estimated values and the true value. MSE is a risk function, corresponding to the expected value of the squared error loss. The fact that MSE is almost always strictly positive (and not zero) is because of randomness or because the estimator does not account for information that could produce a more accurate estimate. In machine learning, specifically empirical risk minimization, MSE may refer to the empirical risk (the average loss on an observed data set), as an estimate of the true MSE (the true risk: the average loss on the actual population distribution).
The MSE is a measure of the quality of an estimator.  As it is derived from the square of Euclidean distance, it is always a positive value that decreases as the error approaches zero.
The MSE is the second moment (about the origin) of the error, and thus incorporates both the variance of the estimator (how widely spread the estimates are from one data sample to another) and its bias (how far off the average estimated value is from the true value). For an unbiased estimator, the MSE is the variance of the estimator. Like the variance, MSE has the same units of measurement as the square of the quantity being estimated. In an analogy to standard deviation, taking the square root of MSE yields the root-mean-square error or root-mean-square deviation (RMSE or RMSD), which has the same units as the quantity being estimated; for an unbiased estimator, the RMSE is the square root of the variance, known as the standard error.

## Related

- [[Mean squared prediction error]]
- [[Common-method variance]]
- [[Hinge loss]]
- [[Huber loss]]
- [[Least-squares spectral analysis]]
- [[Loss function]]
- [[Partial least squares regression]]
- [[Propagation of uncertainty]]
- [[Regularized least squares]]
- [[Root mean square deviation of atomic positions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mean_squared_error