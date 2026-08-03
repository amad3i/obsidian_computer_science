---
title: "Probabilistic context-free grammar"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Probabilistic_context-free_grammar"
wikipedia_categories: ["Bioinformatics", "Formal languages", "Language modeling", "Natural language parsing", "Probabilistic models", "Statistical natural language processing"]
related: ["[[Factored language model]]", "[[Synchronous context-free grammar]]", "[[Brown clustering]]", "[[Collostructional analysis]]", "[[Katz's back-off model]]", "[[Language model]]", "[[Latent Dirichlet allocation]]", "[[N-gram]]", "[[Natural Language Toolkit]]", "[[Probabilistic latent semantic analysis]]"]
---

# Probabilistic context-free grammar

In theoretical linguistics and computational linguistics, probabilistic context free grammars (PCFGs) extend context-free grammars, similar to how hidden Markov models extend regular grammars. Each production is assigned a probability. The probability of a derivation (parse) is the product of the probabilities of the productions used in that derivation. These probabilities can be viewed as parameters of the model, and for large problems it is convenient to learn these parameters via machine learning. A probabilistic grammar's validity is constrained by context of its training dataset.
PCFGs originated from grammar theory, and have application in areas as diverse as natural language processing to the study the structure of RNA molecules and design of programming languages. Designing efficient PCFGs has to weigh factors of scalability and generality. Issues such as grammar ambiguity must be resolved. The grammar design affects results accuracy. Grammar parsing algorithms have various time and memory requirements.

## Related

- [[Factored language model]]
- [[Synchronous context-free grammar]]
- [[Brown clustering]]
- [[Collostructional analysis]]
- [[Katz's back-off model]]
- [[Language model]]
- [[Latent Dirichlet allocation]]
- [[N-gram]]
- [[Natural Language Toolkit]]
- [[Probabilistic latent semantic analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Probabilistic_context-free_grammar