---
title: "Low-rank matrix approximations"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Low-rank_matrix_approximations"
wikipedia_categories: ["Kernel methods for machine learning"]
related: ["[[Fisher kernel]]", "[[Gaussian process]]", "[[Graph kernel]]", "[[Kernel adaptive filter]]", "[[Kernel eigenvoice]]", "[[Kernel methods for vector output]]", "[[Kernel perceptron]]", "[[Kernel principal component analysis]]", "[[Neural network Gaussian process]]", "[[Polynomial kernel]]"]
---

# Low-rank matrix approximations

Low-rank matrix approximations are essential tools in the application of kernel methods to large-scale learning problems.
Kernel methods (for instance, support vector machines or Gaussian processes) project data points into a high-dimensional or infinite-dimensional feature space and find the optimal splitting hyperplane. In the kernel method the data is represented in a kernel matrix (or, Gram matrix). Many algorithms can solve machine learning problems using the kernel matrix. The main problem of kernel method is its high computational cost associated with kernel matrices. The cost is at least quadratic in the number of training data points, but most kernel methods include computation of matrix inversion or eigenvalue decomposition and the cost becomes cubic in the number of training data. Large training sets cause large storage and computational costs. While low rank decomposition methods (Cholesky decomposition) reduce this cost, they still require computing the kernel matrix.  One of the approaches to deal with this problem is low-rank matrix approximations. The most popular examples of them are the Nyström approximation and randomized feature maps approximation methods. Both of them have been successfully applied to efficient kernel learning.

## Related

- [[Fisher kernel]]
- [[Gaussian process]]
- [[Graph kernel]]
- [[Kernel adaptive filter]]
- [[Kernel eigenvoice]]
- [[Kernel methods for vector output]]
- [[Kernel perceptron]]
- [[Kernel principal component analysis]]
- [[Neural network Gaussian process]]
- [[Polynomial kernel]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Low-rank_matrix_approximations