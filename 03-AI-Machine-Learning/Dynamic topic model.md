---
title: "Dynamic topic model"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_topic_model"
wikipedia_categories: ["Latent variable models", "Natural language processing", "Tasks of natural language processing"]
related: ["[[Topic model]]", "[[Automated essay scoring]]", "[[Automatic summarization]]", "[[CLAWS (linguistics)]]", "[[Entity linking]]", "[[Language identification]]", "[[Latent semantic analysis]]", "[[Open information extraction]]", "[[Stemming]]", "[[Text simplification]]"]
---

# Dynamic topic model

Dynamic topic models are generative models in natural language processing that analyze the evolution of latent topics within a collection of documents over time. This family of topic models was proposed by David Blei and John Lafferty and was initially an extension to Latent Dirichlet Allocation (LDA) that can handle sequential documents.
In LDA, both the order the words appear in a document and the order the documents appear in the corpus are oblivious to the model. Whereas words are still assumed to be exchangeable, in a dynamic topic model the order of the documents plays a fundamental role. More precisely, the documents are binned by time period, with the assumption that the topics of each group persist and evolved from the set of the previous slice.
Since its inception, dynamic topic modeling has seen the introduction of several new models, including BERTopic.

## Related

- [[Topic model]]
- [[Automated essay scoring]]
- [[Automatic summarization]]
- [[CLAWS (linguistics)]]
- [[Entity linking]]
- [[Language identification]]
- [[Latent semantic analysis]]
- [[Open information extraction]]
- [[Stemming]]
- [[Text simplification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_topic_model