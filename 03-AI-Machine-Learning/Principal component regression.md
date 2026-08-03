---
title: "Principal component regression"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Principal_component_regression"
wikipedia_categories: ["Factor analysis", "Regression analysis"]
related: ["[[Biplot]]", "[[Calibration (statistics)]]", "[[Confirmatory factor analysis]]", "[[Congruence coefficient]]", "[[Cultural consensus theory]]", "[[Exploratory factor analysis]]", "[[Factor analysis]]", "[[Factor analysis of mixed data]]", "[[Factor regression model]]", "[[FastICA]]"]
---

# Principal component regression

In statistics, principal component regression (PCR) is a regression analysis technique that is based on principal component analysis (PCA). PCR is a form of reduced rank regression. More specifically, PCR is used for estimating the unknown regression coefficients in a standard linear regression model. 
In PCR, instead of regressing the dependent variable on the explanatory variables directly, the principal components of the explanatory variables are used as regressors. One typically uses only a subset of all the principal components for regression, making PCR a kind of regularized procedure and also a type of shrinkage estimator. 
Often the principal components with higher variances (the ones based on eigenvectors corresponding to the higher eigenvalues of the sample variance-covariance matrix of the explanatory variables) are selected as regressors. However, for the purpose of predicting the outcome, the principal components with low variances may also be important, in some cases even more important.
One major use of PCR lies in overcoming the multicollinearity problem which arises when two or more of the explanatory variables are close to being collinear. PCR can aptly deal with such situations by excluding some of the low-variance principal components in the regression step. In addition, by usually regressing on only a subset of all the principal components, PCR can result in dimension reduction through substantially lowering the effective number of parameters characterizing the underlying model. This can be particularly useful in settings with high-dimensional covariates. Also, through appropriate selection of the principal components to be used for regression, PCR can lead to efficient prediction of the outcome based on the assumed model.

## Related

- [[Biplot]]
- [[Calibration (statistics)]]
- [[Confirmatory factor analysis]]
- [[Congruence coefficient]]
- [[Cultural consensus theory]]
- [[Exploratory factor analysis]]
- [[Factor analysis]]
- [[Factor analysis of mixed data]]
- [[Factor regression model]]
- [[FastICA]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Principal_component_regression