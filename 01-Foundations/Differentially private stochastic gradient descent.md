---
title: "Differentially private stochastic gradient descent"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Differentially_private_stochastic_gradient_descent"
wikipedia_categories: ["Differential privacy", "Machine learning", "Optimization algorithms and methods"]
related: ["[[Cross-entropy method]]", "[[Fitness approximation]]", "[[Learning rate]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]"]
---

# Differentially private stochastic gradient descent

Differentially private stochastic gradient descent (DP-SGD) is an algorithmic technique for learning and a refined analysis of privacy costs within the framework of differential privacy. DP-SGD was introduced by Abadi et al. at the 2016 ACM Conference on Computer and Communications Security, where it addresses a fundamental challenge—the privacy-utility trade-off. Stronger privacy requires more noise or larger privacy budgets, which can reduce model accuracy.
DP-SGD has become a de facto standard for privacy-preserving learning from large datasets. It is used in domains with sensitive data, including healthcare and cybersecurity. DP-SGD has been shown to demonstrate that deep neural networks with non-convex objectives can be trained under a modest privacy budget, at a manageable cost in software complexity and model quality. A non-convex objective is one that may have multiple local minima, making optimization more challenging than with convex objectives. Existing approaches require large privacy budgets to train and incur high overheads in computational resources. A privacy budget refers to the total amount of privacy loss allowed over the entire training process. 
DP-SGD follows the same steps as standard stochastic gradient descent (SGD) but clips the gradients' norm to a threshold before adding Gaussian noise.  Gaussian noise is a type of random noise drawn from a normal distribution. Differential privacy is formally defined using the parameters (ε, δ), which bound the privacy loss of any algorithm. DP-SGD tracks privacy loss by a method called the moments accountant. Current implementations use a method called Rényi differential privacy, which provides an even tighter privacy accounting than the original moments accountant. The moments accountant tracks the privacy loss as a random variable at each step. Another privacy-preserving training method is Private Aggregation of Teacher Ensembles (PATE), which uses an ensemble of teacher models to label public data. A teacher model is a model trained on private data that is used to label or provide guidance to another model (the student model).

## Related

- [[Cross-entropy method]]
- [[Fitness approximation]]
- [[Learning rate]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Differentially_private_stochastic_gradient_descent