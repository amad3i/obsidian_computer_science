---
title: "Domain separation"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Domain_separation"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Domain separation

In cryptography, domain separation is a construct used to implement multiple different functions  using only one underlying template in an efficient way. The domain separation can be defined as partitioning of the domain of a function to assign separate subdomains to different applications of the same function.
For example, cryptographic protocols typically rely on random oracles (ROs, functions that return a value fully determined by their input yet otherwise random). The security proofs for these protocols are based on the assumption that the random oracle is unique to the protocol: if two protocols share the same RO, the assumptions of the proof are not met anymore. Since creating a new cryptographic primitive from scratch each time an RO is needed is impractical,  multiple ROs (say, RO1 and RO2) are produced by prepending unique domain separation tags (DSTs, also known as domain separators) to the input of a base oracle RO:

RO1(x) := RO("RO1" || x)
RO2(x) := RO("RO2" || x)
where "RO1" and "RO2" are the strings representing the unique DSTs and || is a concatenation operator. If the underlying RO function is secure (say, it is a cryptographic hash), RO1 and RO2 are statistically independent. The technique was originally proposed by Bellare & Rogaway in 1993.

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

- Wikipedia: https://en.wikipedia.org/wiki/Domain_separation