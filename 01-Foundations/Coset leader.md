---
title: "Coset leader"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Coset_leader"
wikipedia_categories: ["Coding theory", "Computer science stubs", "Cryptography stubs", "Error detection and correction"]
related: ["[[Alternant code]]", "[[Srivastava code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Delsarte–Goethals code]]"]
---

# Coset leader

In coding theory, a coset leader is a word of minimum weight in any particular coset - that is, a word with the lowest amount of non-zero entries. Sometimes there are several words of equal minimum weight in a coset, and in that case, any one of those words may be chosen to be the coset leader.
Coset leaders are used in the construction of a standard array for a linear code, which can then be used to decode received vectors. For a received vector y, the decoded message is y - e, where e is the coset leader of y. Coset leaders can also be used to construct a fast decoding strategy. For each coset leader u we calculate the syndrome uH′. When we receive v we evaluate vH′ and find the matching syndrome. The corresponding coset leader is the most likely error pattern and we assume that v+u was the codeword sent.

## Related

- [[Alternant code]]
- [[Srivastava code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Delsarte–Goethals code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Coset_leader