---
title: "Latent Dirichlet allocation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation"
wikipedia_categories: ["Bayesian networks", "Latent variable models", "Population genetics", "Probabilistic models", "Statistical natural language processing"]
related: ["[[Factored language model]]", "[[Mixture model]]", "[[Pachinko allocation]]", "[[Probabilistic context-free grammar]]", "[[Probabilistic latent semantic analysis]]", "[[Stochastic grammar]]", "[[Additive smoothing]]", "[[Bayesian hierarchical modeling]]", "[[Brown clustering]]", "[[Causal Markov condition]]"]
---

# Latent Dirichlet allocation

In natural language processing, latent Dirichlet allocation (LDA) is a generative statistical model that explains how a collection of text documents can be described by a set of unobserved "topics." For example, given a set of news articles, LDA might discover that one topic is characterized by words like "president", "government", and "election", while another is characterized by "team", "game", and "score". It is one of the most common topic models.
The LDA model was first presented as a graphical model for population genetics by J. K. Pritchard, M. Stephens and P. Donnelly in 2000. The model was subsequently applied to machine learning by David Blei, Andrew Ng, and Michael I. Jordan in 2003. Although its most frequent application is in modeling text corpora, it has also been used for other problems, such as in clinical psychology, social science, and computational musicology.
The core assumption of LDA is that documents are represented as a random mixture of latent topics, and each topic is characterized by a probability distribution over words. The model is a generalization of probabilistic latent semantic analysis (pLSA), differing primarily in that LDA treats the topic mixture as a Dirichlet prior, leading to more reasonable mixtures and less susceptibility to overfitting. Learning the latent topics and their associated probabilities from a corpus is typically done using Bayesian inference, often with methods like Gibbs sampling or variational Bayes.

## Related

- [[Factored language model]]
- [[Mixture model]]
- [[Pachinko allocation]]
- [[Probabilistic context-free grammar]]
- [[Probabilistic latent semantic analysis]]
- [[Stochastic grammar]]
- [[Additive smoothing]]
- [[Bayesian hierarchical modeling]]
- [[Brown clustering]]
- [[Causal Markov condition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation