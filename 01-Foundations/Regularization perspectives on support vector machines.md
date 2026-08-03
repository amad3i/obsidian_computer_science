---
title: "Regularization perspectives on support vector machines"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Regularization_perspectives_on_support_vector_machines"
wikipedia_categories: ["Mathematical analysis", "Support vector machines"]
related: ["[[Automorphic number]]", "[[Carleman's condition]]", "[[Cauchy–Schwarz inequality]]", "[[Discrete calculus]]", "[[Finite difference]]", "[[H square]]", "[[Hinge loss]]", "[[Hypostatic abstraction]]", "[[Identity channel]]", "[[Least-squares spectral analysis]]"]
---

# Regularization perspectives on support vector machines

Within mathematical analysis, regularization perspectives on support-vector machines provide a way of interpreting support-vector machines (SVMs) in the context of other regularization-based machine-learning algorithms.  SVM algorithms categorize binary data, with the goal of fitting the training set data in a way that minimizes the average of the hinge-loss function and L2 norm of the learned weights. This strategy avoids overfitting via Tikhonov regularization and in the L2 norm sense and also corresponds to minimizing the bias and variance of our estimator of the weights. Estimators with lower mean squared error predict better or generalize better when given unseen data.
Specifically, Tikhonov regularization algorithms produce a decision boundary that minimizes the average training-set error and constrain the decision boundary not to be excessively complicated or overfit the training data via a L2 norm of the weights term. The training and test-set errors can be measured without bias and in a fair way using accuracy, precision, Auc-Roc, precision-recall, and other metrics. 
Regularization perspectives on support-vector machines interpret SVM as a special case of Tikhonov regularization, specifically Tikhonov regularization with the hinge loss for a loss function.  This provides a theoretical framework with which to analyze SVM algorithms and compare them to other algorithms with the same goals: to generalize without overfitting. SVM was first proposed in 1995 by Corinna Cortes and Vladimir Vapnik, and framed geometrically as a method for finding hyperplanes that can separate multidimensional data into two categories. This traditional geometric interpretation of SVMs provides useful intuition about how SVMs work, but is difficult to relate to other machine-learning techniques for avoiding overfitting, like regularization, early stopping, sparsity and Bayesian inference.  However, once it was discovered that SVM is also a special case of Tikhonov regularization, regularization perspectives on SVM provided the theory necessary to fit SVM within a broader class of algorithms. This has enabled detailed comparisons between SVM and other forms of Tikhonov regularization, and theoretical grounding for why it is beneficial to use SVM's loss function, the hinge loss.

## Related

- [[Automorphic number]]
- [[Carleman's condition]]
- [[Cauchy–Schwarz inequality]]
- [[Discrete calculus]]
- [[Finite difference]]
- [[H square]]
- [[Hinge loss]]
- [[Hypostatic abstraction]]
- [[Identity channel]]
- [[Least-squares spectral analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Regularization_perspectives_on_support_vector_machines