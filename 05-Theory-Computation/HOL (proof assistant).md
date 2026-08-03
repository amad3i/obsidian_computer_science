---
title: "HOL (proof assistant)"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/HOL_(proof_assistant)"
wikipedia_categories: ["Logic in computer science", "Proof assistants", "Software using the BSD license"]
related: ["[[ACL2]]", "[[HOL Light]]", "[[Isabelle (proof assistant)]]", "[[Logic for Computable Functions]]", "[[Logical framework]]", "[[1-in-3-SAT]]", "[[Abstract rewriting system]]", "[[ACM Transactions on Computational Logic]]", "[[Agent verification]]", "[[Agentive logic]]"]
---

# HOL (proof assistant)

HOL (Higher Order Logic) denotes a family of interactive theorem proving systems using similar (higher-order) logics and implementation strategies. Systems in this family follow the LCF (Logic for Computable Functions) approach as they are implemented as a library which defines an abstract data type of proven theorems such that new objects of this type can only be created using the functions in the library which correspond to inference rules in higher-order logic. As long as these functions are correctly implemented, all theorems proven in the system must be valid. As such, a large system can be built on top of a small trusted kernel.
Systems in the HOL family use ML or its successors. ML was originally developed along with LCF as a meta-language for theorem proving systems; in fact, the name stands for "Meta-Language".

## Related

- [[ACL2]]
- [[HOL Light]]
- [[Isabelle (proof assistant)]]
- [[Logic for Computable Functions]]
- [[Logical framework]]
- [[1-in-3-SAT]]
- [[Abstract rewriting system]]
- [[ACM Transactions on Computational Logic]]
- [[Agent verification]]
- [[Agentive logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HOL_(proof_assistant)