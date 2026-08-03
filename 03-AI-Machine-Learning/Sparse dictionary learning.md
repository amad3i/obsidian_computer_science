---
title: "Sparse dictionary learning"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Sparse_dictionary_learning"
wikipedia_categories: ["Unsupervised learning"]
related: ["[[Cognitive computer]]", "[[Competitive learning]]", "[[Conceptual clustering]]", "[[Foundation model]]", "[[Generative adversarial network]]", "[[Geospatial foundation model]]", "[[Graph neural network]]", "[[Hallucination (artificial intelligence)]]", "[[Hierarchical temporal memory]]", "[[K-means clustering]]"]
---

# Sparse dictionary learning

Sparse dictionary learning (also known as sparse coding or SDL) is a representation learning method which aims to find a sparse representation of the input data in the form of a linear combination of basic elements as well as those basic elements themselves. These elements are called atoms, and they compose a dictionary. Atoms in the dictionary are not required to be orthogonal, and they may be an over-complete spanning set. This problem setup also allows the dimensionality of the signals being represented to be higher than any one of the signals being observed. These two properties lead to having seemingly redundant atoms that allow multiple representations of the same signal, but also provide an improvement in sparsity and flexibility of the representation.
One of the most important applications of sparse dictionary learning is in the field of compressed sensing or signal recovery. In compressed sensing, a high-dimensional signal can be recovered with only a few linear measurements, provided that the signal is sparse or near-sparse. Since not all signals satisfy this condition, it is crucial to find a sparse representation of that signal such as the wavelet transform or the directional gradient of a rasterized matrix. Once a matrix or a high-dimensional vector is transferred to a sparse space, different recovery algorithms like basis pursuit, CoSaMP, or fast non-iterative algorithms can be used to recover the signal.
One of the key principles of dictionary learning is that the dictionary has to be inferred from the input data. The emergence of sparse dictionary learning methods was stimulated by the fact that in signal processing, one typically wants to represent the input data using a minimal amount of components. Before this approach, the general practice was to use predefined dictionaries such as Fourier or wavelet transforms. However, in certain cases, a dictionary that is trained to fit the input data can significantly improve the sparsity, which has applications in data decomposition, compression, and analysis, and has been used in the fields of image denoising and classification, and video and audio processing. Sparsity and overcomplete dictionaries have immense applications in image compression, image fusion, and inpainting.

## Related

- [[Cognitive computer]]
- [[Competitive learning]]
- [[Conceptual clustering]]
- [[Foundation model]]
- [[Generative adversarial network]]
- [[Geospatial foundation model]]
- [[Graph neural network]]
- [[Hallucination (artificial intelligence)]]
- [[Hierarchical temporal memory]]
- [[K-means clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sparse_dictionary_learning