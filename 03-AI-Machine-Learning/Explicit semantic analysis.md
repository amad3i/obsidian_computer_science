---
title: "Explicit semantic analysis"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Explicit_semantic_analysis"
wikipedia_categories: ["Natural language processing", "Vector space model"]
related: ["[[Abdul Majid Bhurgri Institute of Language Engineering]]", "[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Affix grammar over a finite lattice]]", "[[AFNLP]]", "[[Aggregation (linguistics)]]", "[[AI data center]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[AsoSoft text corpus]]"]
---

# Explicit semantic analysis

In natural language processing and information retrieval, explicit semantic analysis (ESA) is a vectoral representation of text (individual words or entire documents) that uses a document corpus as a knowledge base. Specifically, in ESA, a word is represented as a column vector in the tf–idf matrix of the text corpus and a document (string of words) is represented as the centroid of the vectors representing its words. Typically, the text corpus is English Wikipedia, though other corpora including the Open Directory Project have been used.
ESA was designed by Evgeniy Gabrilovich and Shaul Markovitch as a means of improving text categorization
and has been used by this pair of researchers to compute what they refer to as "semantic relatedness" by means of cosine similarity between the aforementioned vectors, collectively interpreted as a space of "concepts explicitly defined and described by humans", where Wikipedia articles (or ODP entries, or otherwise titles of documents in the knowledge base corpus) are equated with concepts. The name "explicit semantic analysis" contrasts with latent semantic analysis (LSA), because the use of a knowledge base makes it possible to assign human-readable labels to the concepts that make up the vector space.

## Related

- [[Abdul Majid Bhurgri Institute of Language Engineering]]
- [[ACL Data Collection Initiative]]
- [[Adversarial stylometry]]
- [[Affix grammar over a finite lattice]]
- [[AFNLP]]
- [[Aggregation (linguistics)]]
- [[AI data center]]
- [[Arabic Ontology]]
- [[Artificial intelligence content detection]]
- [[AsoSoft text corpus]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Explicit_semantic_analysis