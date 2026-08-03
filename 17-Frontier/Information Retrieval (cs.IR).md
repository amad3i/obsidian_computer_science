---
title: "Information Retrieval"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.IR/recent"
---

# Information Retrieval (cs.IR)

Frontier research area. Live listing: https://arxiv.org/list/cs.IR/recent

## Recent papers (real, from arXiv)

### QASP: Query-Adaptive Robust Vector Search Policy

A fundamental challenge of vector search is achieving consistently high recall while minimizing computational costs. Fixed search parameters cause significant performance variance across queries, and conventional evaluation on average recall masks these per-query disparities. We introduce QASP (Query-Adaptive robust vector Search Policy), which predicts the complete recall progression curve per query via a single upfront supervised regression, from which a search policy is derived for any recall target; this avoids iterative model invocations during search or separate predictors per target. By predicting normalized recall values with scale-invariant features and pre-search inference, QASP generalizes across recall targets, index configurations, and datasets. Its fine-grained progress predictions further enable a lightweight reactive complement that adjusts search depth based on predicted

- http://arxiv.org/abs/2607.29606v1

### Bridging the Question-Answer Gap in Retrieval-Augmented Generation: Hypothetical Prompt Embeddings

Retrieval-Augmented Generation (RAG) systems synergize retrieval mechanisms with generative language models to enhance the accuracy and relevance of responses. However, bridging the style gap between user queries and relevant information in document text remains a persistent challenge in retrieval-augmented systems, often addressed by runtime solutions (e.g., Hypothetical Document Embeddings (HyDE)) that attempt to improve alignment but introduce extra computational overhead at query time. To address these challenges, we propose Hypothetical Prompt Embeddings (HyPE), a framework that shifts the generation of hypothetical content from query time to the indexing phase. By precomputing multiple hypothetical prompts for each data chunk and embedding the chunk in place of the prompt, HyPE transforms retrieval into a question-question matching task, bypassing the need for runtime synthetic ans

- http://arxiv.org/abs/2607.29402v1

### Language Models Agree With Each Other, Not With Readers

Claims that language models homogenise are usually measured against human judgements collected for the study, which makes the human side an artifact of the design: a crowdworker given the model's instruction is running the model's prompt. We measure convergence against a human reference nobody built for the purpose -- 2,523 reader mark sets across 120 web documents, produced by people highlighting for their own reasons on a platform where the overlay of others' marks is off by default. Agreement is the overlap between two size-matched sentence sets minus the overlap expected when each is resampled within its own depth-and-length bands. The null's calibration is demonstrated, not asserted: every pair involving a random baseline lands within 0.006 of zero. On the median document each party names 14 sentences of 70; two readers share 4.1 and two models 8.7. Across 18 model arms spanning 11 

- http://arxiv.org/abs/2607.29274v1

## Sources

- https://arxiv.org/list/cs.IR/recent