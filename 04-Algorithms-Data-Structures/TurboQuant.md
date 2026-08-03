---
title: "TurboQuant"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/TurboQuant"
wikipedia_categories: ["Algorithms", "Data compression", "Data mining", "Information retrieval", "Lossy compression algorithms"]
related: ["[[Argument mining]]", "[[Discrete cosine transform]]", "[[Line spectral pairs]]", "[[Linear predictive coding]]", "[[Sardinas–Patterson algorithm]]", "[[Wiener connector]]", "[[Action model learning]]", "[[Adamic–Adar index]]", "[[Adaptive algorithm]]", "[[Affinity analysis]]"]
---

# TurboQuant

TurboQuant is an online vector quantization algorithm for compressing high-dimensional Euclidean vectors while preserving their geometric structure. It was proposed in 2025 by Amir Zandieh, Majid Daliri, Majid Hadian, and Vahab Mirrokni in the paper TurboQuant: Online Vector Quantization with Near-optimal Distortion Rate. The paper lists Zandieh and Mirrokni as affiliated with Google Research, Daliri with New York University, and Hadian with Google DeepMind. The method was developed for applications including large language model (LLM) inference, key–value (KV) cache compression, vector databases, and nearest neighbor search.
TurboQuant consists of two related algorithms: TurboQuantmse, which is optimized for mean squared error (MSE), and TurboQuantprod, which is optimized for unbiased inner product estimation. The algorithm uses a random rotation of input vectors, applies scalar quantizers to the rotated coordinates, and, for inner-product estimation, applies a one-bit Quantized Johnson–Lindenstrauss (QJL) transform to the residual error.

## Related

- [[Argument mining]]
- [[Discrete cosine transform]]
- [[Line spectral pairs]]
- [[Linear predictive coding]]
- [[Sardinas–Patterson algorithm]]
- [[Wiener connector]]
- [[Action model learning]]
- [[Adamic–Adar index]]
- [[Adaptive algorithm]]
- [[Affinity analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TurboQuant