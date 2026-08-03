---
title: "Latent space"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Latent_space"
wikipedia_categories: ["Cluster analysis", "Data mining"]
related: ["[[Archetypal analysis]]", "[[Cluster analysis]]", "[[Frequent pattern discovery]]", "[[Action model learning]]", "[[Adamic–Adar index]]", "[[Affinity analysis]]", "[[Agent mining]]", "[[AMiner (database)]]", "[[Anomaly detection]]", "[[Argument mining]]"]
---

# Latent space

A latent space, also known as a latent feature space or embedding space, is an embedding of a set of items within a manifold in which items resembling each other are positioned closer to one another. Position within the latent space can be viewed as being defined by a set of latent variables that emerge from the resemblances between the objects.
In most cases, the dimensionality of the latent space is chosen to be lower than the dimensionality of the feature space from which the data points are drawn, making the construction of a latent space an example of dimensionality reduction, which can also be viewed as a form of data compression. Latent spaces are usually fit via machine learning, and they can then be used as feature spaces in machine learning models, including classifiers and other supervised predictors.
The interpretation of latent spaces in machine learning models is an ongoing area of research, but achieving clear interpretations remains challenging. The black-box nature of these models often makes the latent space unintuitive, while its high-dimensional, complex, and nonlinear characteristics further complicate the task of understanding it. Analysis of the latent space geometry of diffusion models reveals a fractal structure of phase transitions in the latent space, characterized by abrupt changes in the Fisher information metric.
Some visualization techniques have been developed to connect the latent space to the visual world, but there is often not a direct connection between the latent space interpretation and the model itself. Such techniques include t-distributed stochastic neighbor embedding (t-SNE), where the latent space is mapped to two dimensions for visualization. Latent space distances lack physical units, so the interpretation of these distances may depend on the application.

## Related

- [[Archetypal analysis]]
- [[Cluster analysis]]
- [[Frequent pattern discovery]]
- [[Action model learning]]
- [[Adamic–Adar index]]
- [[Affinity analysis]]
- [[Agent mining]]
- [[AMiner (database)]]
- [[Anomaly detection]]
- [[Argument mining]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Latent_space