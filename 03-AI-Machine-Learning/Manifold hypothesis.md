---
title: "Manifold hypothesis"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Manifold_hypothesis"
wikipedia_categories: ["Machine learning", "Theoretical computer science"]
related: ["[[Granular computing]]", "[[Machine learning in physics]]", "[[Pattern language (formal languages)]]", "[[Quantum machine learning]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]"]
---

# Manifold hypothesis

The manifold hypothesis posits that many high-dimensional data sets that occur in the real world actually lie along low-dimensional latent manifolds inside that high-dimensional space. As a consequence of the manifold hypothesis, many data sets that appear to initially require many variables to describe, can actually be described by a comparatively small number of variables, linked to the local coordinate system of the underlying manifold. It is suggested that this principle underpins the effectiveness of machine learning algorithms in describing high-dimensional data sets by considering a few common features.
The manifold hypothesis is related to the effectiveness of nonlinear dimensionality reduction techniques in machine learning. Many techniques of dimensional reduction make the assumption that data lies along a low-dimensional submanifold, such as manifold sculpting, manifold alignment, and manifold regularization.
The major implications of this hypothesis is that

Machine learning models only have to fit relatively simple, low-dimensional, highly structured subspaces within their potential input space (latent manifolds).
Within one of these manifolds, it's always possible to interpolate between two inputs, that is to say, morph one into another via a continuous path along which all points fall on the manifold.
The ability to interpolate between samples is the key to generalization in deep learning.

## Related

- [[Granular computing]]
- [[Machine learning in physics]]
- [[Pattern language (formal languages)]]
- [[Quantum machine learning]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Manifold_hypothesis