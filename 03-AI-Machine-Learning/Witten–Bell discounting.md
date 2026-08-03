---
title: "Witten–Bell discounting"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Witten–Bell_discounting"
wikipedia_categories: ["Algorithms", "Natural language processing"]
related: ["[[Text-to-video model]]", "[[Abdul Majid Bhurgri Institute of Language Engineering]]", "[[ACL Data Collection Initiative]]", "[[Adaptive algorithm]]", "[[Adversarial stylometry]]", "[[Affix grammar over a finite lattice]]", "[[AFNLP]]", "[[Aggregation (linguistics)]]", "[[AI data center]]", "[[Algorism]]"]
---

# Witten–Bell discounting

In natural language processing, Witten-Bell discounting is a method that can address the sparse data and zero-frequency issues in N-gram algorithms. It was first proposed by Ian Witten and Tim Bell in 1991. 
A word that hasn't been encountered before is considered unseen, thus zero-frequency N-gram refers to an occurrence that has yet to take place; when it does, it will mark the initial instance we observe this new N-gram. Thus, the likelihood of encountering a zero-frequency N-gram can be represented by the likelihood of encountering an N-gram for the initial time. The idea behind Witten-Bell is the application of the number of items we have encountered once to assist in estimating the number of items never encountered. 
Utilizing this method, we can remove obtaining zero probability values for transition probability and maximum likelihood estimation for a series of words (N-gram) that is encountered for the first time in our algorithm.

## Related

- [[Text-to-video model]]
- [[Abdul Majid Bhurgri Institute of Language Engineering]]
- [[ACL Data Collection Initiative]]
- [[Adaptive algorithm]]
- [[Adversarial stylometry]]
- [[Affix grammar over a finite lattice]]
- [[AFNLP]]
- [[Aggregation (linguistics)]]
- [[AI data center]]
- [[Algorism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Witten–Bell_discounting