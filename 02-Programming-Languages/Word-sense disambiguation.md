---
title: "Word-sense disambiguation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Word-sense_disambiguation"
wikipedia_categories: ["Ambiguity", "Computational linguistics", "Lexical semantics", "Natural language processing", "Semantics", "Word-sense disambiguation"]
related: ["[[Word-sense induction]]", "[[Automatic acquisition of sense-tagged corpora]]", "[[Lesk algorithm]]", "[[Lexical substitution]]", "[[Temporal annotation]]", "[[Babelfy]]", "[[BulSemCor]]", "[[Classic monolingual word-sense disambiguation]]", "[[Computational semantics]]", "[[Minimal recursion semantics]]"]
---

# Word-sense disambiguation

Word-sense disambiguation, or simply disambiguation, is the process of identifying which sense of a word is meant in a sentence or other segment of context. In human language processing and cognition, it is usually subconscious.
Given that natural language requires reflection of neurological reality, as shaped by the abilities provided by the brain's neural networks, computer science has had a long-term challenge in developing the ability in computers to do natural language processing and machine learning.
Many techniques have been researched, including dictionary-based methods that use the knowledge encoded in lexical resources, supervised machine learning methods in which a classifier is trained for each distinct word on a corpus of manually sense-annotated examples, and completely unsupervised methods that cluster occurrences of words, thereby inducing word senses. Among these, supervised learning approaches have been the most successful algorithms to date.
The accuracy of current algorithms is difficult to state without a host of caveats. In English, accuracy at the coarse-grained (homograph) level is routinely above 90% (as of 2009), with some methods on particular homographs achieving over 96%. On finer-grained sense distinctions, top accuracies from 59.1% to 69.0% have been reported in evaluation exercises (SemEval-2007, Senseval-2), where the baseline accuracy of the simplest possible algorithm of always choosing the most frequent sense was 51.4% and 57%, respectively.

## Related

- [[Word-sense induction]]
- [[Automatic acquisition of sense-tagged corpora]]
- [[Lesk algorithm]]
- [[Lexical substitution]]
- [[Temporal annotation]]
- [[Babelfy]]
- [[BulSemCor]]
- [[Classic monolingual word-sense disambiguation]]
- [[Computational semantics]]
- [[Minimal recursion semantics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Word-sense_disambiguation