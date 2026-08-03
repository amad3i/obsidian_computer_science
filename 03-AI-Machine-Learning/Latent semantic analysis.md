---
title: "Latent semantic analysis"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Latent_semantic_analysis"
wikipedia_categories: ["Information retrieval techniques", "Latent variable models", "Natural language processing", "Semantic relations"]
related: ["[[Dynamic topic model]]", "[[Latent semantic mapping]]", "[[Natural-language user interface]]", "[[Query understanding]]", "[[Semantic space]]", "[[Stemming]]", "[[Topic model]]", "[[Vocabulary mismatch]]", "[[Word embedding]]", "[[Abdul Majid Bhurgri Institute of Language Engineering]]"]
---

# Latent semantic analysis

Latent semantic analysis (LSA) is a technique in natural language processing, in particular distributional semantics, of analyzing relationships between a set of documents and the terms they contain by producing a set of concepts related to the documents and terms. LSA assumes that words that are close in meaning will occur in similar pieces of text (the distributional hypothesis). A matrix containing word counts per document (rows represent unique words and columns represent each document) is constructed from a large piece of text and a mathematical technique called singular value decomposition (SVD) is used to reduce the number of rows while preserving the similarity structure among columns. Documents are then compared by cosine similarity between any two columns. Values close to 1 represent very similar documents while values close to 0 represent very dissimilar documents.
An information retrieval technique using latent semantic structure was patented in 1988 by Scott Deerwester, Susan Dumais, George Furnas, Richard Harshman, Thomas Landauer, Karen Lochbaum and Lynn Streeter. In the context of its application to information retrieval, it is sometimes called latent semantic indexing (LSI).

## Related

- [[Dynamic topic model]]
- [[Latent semantic mapping]]
- [[Natural-language user interface]]
- [[Query understanding]]
- [[Semantic space]]
- [[Stemming]]
- [[Topic model]]
- [[Vocabulary mismatch]]
- [[Word embedding]]
- [[Abdul Majid Bhurgri Institute of Language Engineering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Latent_semantic_analysis