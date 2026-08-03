---
title: "Forking lemma"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Forking_lemma"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Forking lemma

The forking lemma is any of a number of related lemmas in cryptography research. The lemma states that if an adversary (typically a probabilistic Turing machine), on inputs drawn from some distribution, produces an output that has some property with non-negligible probability, then with non-negligible probability, if the adversary is re-run on new inputs but with the same random tape, its second output will also have the property.
This concept was first used by David Pointcheval and Jacques Stern in "Security proofs for signature schemes," published in the proceedings of Eurocrypt 1996. In their paper, the forking lemma is specified in terms of an adversary that attacks a digital signature scheme instantiated in the random oracle model. They show that if an adversary can forge a signature with non-negligible probability, then there is a non-negligible probability that the same adversary with the same random tape can create a second forgery in an attack with a different random oracle. The forking lemma was later generalized by Mihir Bellare and Gregory Neven. The forking lemma has been used and further generalized to prove the security of a variety of digital signature schemes and other random-oracle based cryptographic constructions.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]
- [[Batch cryptography]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Forking_lemma