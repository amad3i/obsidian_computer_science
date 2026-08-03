---
title: "Second-order co-occurrence pointwise mutual information"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Second-order_co-occurrence_pointwise_mutual_information"
wikipedia_categories: ["Computational linguistics", "Lexical semantics", "Natural language processing", "Statistical distance"]
related: ["[[Temporal annotation]]", "[[Word-sense disambiguation]]", "[[Word-sense induction]]", "[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Aggregation (linguistics)]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[Association for Computational Linguistics]]", "[[Automated essay scoring]]"]
---

# Second-order co-occurrence pointwise mutual information

In computational linguistics, second-order co-occurrence pointwise mutual information (SOC-PMI) is a method used to measure semantic similarity, or how close in meaning two words are. The method does not require the two words to appear together in a text. Instead, it works by analyzing the "neighbor" words that typically appear alongside each of the two target words in a large body of text (corpus). If the two target words frequently share the same neighbors, they are considered semantically similar. 
For example, the words "cemetery" and "graveyard" may not appear in the same sentence often, but they both frequently appear near words like "buried," "dead," and "funeral." SOC-PMI uses this shared context to determine that they have a similar meaning. 
The method is called "second-order" because it doesn't look at the direct co-occurrence of the target words (which would be first-order), but at the co-occurrence of their neighbors (a second level of association). The strength of these associations is quantified using pointwise mutual information (PMI).

## Related

- [[Temporal annotation]]
- [[Word-sense disambiguation]]
- [[Word-sense induction]]
- [[ACL Data Collection Initiative]]
- [[Adversarial stylometry]]
- [[Aggregation (linguistics)]]
- [[Arabic Ontology]]
- [[Artificial intelligence content detection]]
- [[Association for Computational Linguistics]]
- [[Automated essay scoring]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Second-order_co-occurrence_pointwise_mutual_information