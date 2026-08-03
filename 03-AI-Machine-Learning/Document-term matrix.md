---
title: "Document-term matrix"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Document-term_matrix"
wikipedia_categories: ["Natural language processing"]
related: ["[[Abdul Majid Bhurgri Institute of Language Engineering]]", "[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Affix grammar over a finite lattice]]", "[[AFNLP]]", "[[Aggregation (linguistics)]]", "[[AI data center]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[AsoSoft text corpus]]"]
---

# Document-term matrix

A document-term matrix is a mathematical matrix that describes the frequency of terms that occur in each document in a collection. In a document-term matrix, rows correspond to documents in the collection and columns correspond to terms. This matrix is a specific instance of a document-feature matrix where "features" may refer to other properties of a document besides terms. It is also common to encounter the transpose, or term-document matrix where documents are the columns and terms are the rows. They are useful in the field of natural language processing and computational text analysis.
While the value of the cells is commonly the raw count of a given term, there are various schemes for weighting the raw counts such as row normalizing (i.e. relative frequency/proportions) and tf-idf.
Terms are commonly single words separated by whitespace or punctuation on either side (a.k.a. unigrams). In such a case, this is also referred to as "bag of words" representation because the counts of individual words is retained, but not the order of the words in the document.

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

- Wikipedia: https://en.wikipedia.org/wiki/Document-term_matrix