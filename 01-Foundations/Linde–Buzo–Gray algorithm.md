---
title: "Linde–Buzo–Gray algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Linde–Buzo–Gray_algorithm"
wikipedia_categories: ["Artificial neural networks", "Cluster analysis algorithms", "Machine learning algorithms", "Signal processing"]
related: ["[[Self-organizing map]]", "[[Backpropagation]]", "[[Dehaene–Changeux model]]", "[[Growing self-organizing map]]", "[[Hyper basis function network]]", "[[K-means clustering]]", "[[Kernel principal component analysis]]", "[[Leabra]]", "[[LoRA (machine learning)]]", "[[Quickprop]]"]
---

# Linde–Buzo–Gray algorithm

The Linde–Buzo–Gray algorithm (named after its creators Yoseph Linde, Andrés Buzo and Robert M. Gray, who designed it in 1980) is an iterative vector quantization algorithm to improve a small set of vectors (codebook) to represent a larger set of vectors (training set), such that it will be locally optimal. It combines Lloyd's Algorithm with a splitting technique in which larger codebooks are built from smaller codebooks by splitting each code vector in two. The core idea of the algorithm is that by splitting the codebook such that all code vectors from the previous codebook are present, the new codebook must be as good as the previous one or better.

## Related

- [[Self-organizing map]]
- [[Backpropagation]]
- [[Dehaene–Changeux model]]
- [[Growing self-organizing map]]
- [[Hyper basis function network]]
- [[K-means clustering]]
- [[Kernel principal component analysis]]
- [[Leabra]]
- [[LoRA (machine learning)]]
- [[Quickprop]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linde–Buzo–Gray_algorithm