---
title: "W-shingling"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/W-shingling"
wikipedia_categories: ["Natural language processing"]
related: ["[[Abdul Majid Bhurgri Institute of Language Engineering]]", "[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Affix grammar over a finite lattice]]", "[[AFNLP]]", "[[Aggregation (linguistics)]]", "[[AI data center]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[AsoSoft text corpus]]"]
---

# W-shingling

In natural language processing a w-shingling is a set of unique shingles (therefore n-grams) each of which is composed of contiguous subsequences of tokens within a document, which can then be used to ascertain the similarity between documents.  The symbol w denotes the quantity of tokens in each shingle selected, or solved for.
The document, "a rose is a rose is a rose" can therefore be maximally tokenized as follows:

(a,rose,is,a,rose,is,a,rose)
The set of all contiguous sequences of 4 tokens (Thus 4=n, thus 4-grams) is

{ (a,rose,is,a), (rose,is,a,rose), (is,a,rose,is), (a,rose,is,a), (rose,is,a,rose) }
Which can then be reduced, or maximally shingled in this particular instance to

{ (a,rose,is,a), (rose,is,a,rose), (is,a,rose,is) }.

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

- Wikipedia: https://en.wikipedia.org/wiki/W-shingling