---
title: "Operational semantics"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Operational_semantics"
wikipedia_categories: ["Formal specification languages", "Logic in computer science", "Operational semantics", "Programming language semantics"]
related: ["[[Algebraic semantics (computer science)]]", "[[Axiomatic semantics]]", "[[Denotational semantics]]", "[[Semantics (programming languages)]]", "[[OBJ (programming language)]]", "[[1-in-3-SAT]]", "[[Abstract rewriting system]]", "[[ACM Transactions on Computational Logic]]", "[[Agent verification]]", "[[Agentive logic]]"]
---

# Operational semantics

Operational semantics is a category of formal programming language semantics in which certain desired properties of a program, such as correctness, safety or security, are verified by constructing proofs from logical statements about its execution and procedures, rather than by attaching mathematical meanings to its terms (denotational semantics). Operational semantics are classified in two categories: structural operational semantics (or small-step semantics) formally describe how the individual steps of a computation take place in a computer-based system; by opposition natural semantics (or big-step semantics) describe how the overall results of the executions are obtained. Other approaches to providing a formal semantics of programming languages include axiomatic semantics, denotational semantics, and algebraic semantics.
The operational semantics for a programming language describes how a valid program is interpreted as sequences of computational steps. These sequences then are the meaning of the program. In the context of functional programming, the final step in a terminating sequence returns the value of the program. (In general there can be many return values for a single program, because the program could be nondeterministic, and even for a deterministic program there can be many computation sequences since the semantics may not specify exactly what sequence of operations arrives at that value.)
Perhaps the first formal incarnation of operational semantics was the use of the lambda calculus to define the semantics of Lisp. Abstract machines in the tradition of the SECD machine are also closely related.

## Related

- [[Algebraic semantics (computer science)]]
- [[Axiomatic semantics]]
- [[Denotational semantics]]
- [[Semantics (programming languages)]]
- [[OBJ (programming language)]]
- [[1-in-3-SAT]]
- [[Abstract rewriting system]]
- [[ACM Transactions on Computational Logic]]
- [[Agent verification]]
- [[Agentive logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Operational_semantics