---
title: "Katz's back-off model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Katz's_back-off_model"
wikipedia_categories: ["Language modeling", "Statistical natural language processing"]
related: ["[[Brown clustering]]", "[[Factored language model]]", "[[Language model]]", "[[Probabilistic context-free grammar]]", "[[Probabilistic latent semantic analysis]]", "[[Additive smoothing]]", "[[Cache language model]]", "[[Collostructional analysis]]", "[[Dissociated press]]", "[[Distributional–relational database]]"]
---

# Katz's back-off model

Katz back-off is a generative n-gram language model that estimates the conditional probability of a word given its history in the n-gram. It accomplishes this estimation by backing off through progressively shorter history models under certain conditions. By doing so, the model with the most reliable information about a given history is used to provide the better results.
The model was introduced in 1987 by Slava M. Katz. Prior to that, n-gram language models were constructed by training individual models for different n-gram orders using maximum likelihood estimation and then interpolating them together.

## Related

- [[Brown clustering]]
- [[Factored language model]]
- [[Language model]]
- [[Probabilistic context-free grammar]]
- [[Probabilistic latent semantic analysis]]
- [[Additive smoothing]]
- [[Cache language model]]
- [[Collostructional analysis]]
- [[Dissociated press]]
- [[Distributional–relational database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Katz's_back-off_model