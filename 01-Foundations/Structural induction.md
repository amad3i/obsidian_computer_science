---
title: "Structural induction"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Structural_induction"
wikipedia_categories: ["Graph theory", "Logic in computer science", "Mathematical induction", "Mathematical logic", "Mathematical proofs", "Wellfoundedness"]
related: ["[[Friedman's SSCG function]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Bunched logic]]", "[[Game semantics]]", "[[Kruskal's tree theorem]]", "[[Mathematical induction]]", "[[Mathematical proof]]", "[[Model theory]]", "[[Original proof of Gödel's completeness theorem]]", "[[Peano axioms]]"]
---

# Structural induction

Structural induction is a proof method that is used in mathematical logic (e.g., in the proof of Łoś' theorem), computer science, graph theory, and some other mathematical fields.  It is a generalization of mathematical induction over natural numbers and can be further generalized to arbitrary Noetherian induction.  Structural recursion is a recursion method bearing the same relationship to structural induction as ordinary recursion bears to ordinary mathematical induction.
Structural induction is used to prove that some proposition P(x) holds for all x of some sort of recursively defined structure, such as
formulas, lists, or trees.  A well-founded partial order is defined on the structures ("subformula" for formulas, "sublist" for lists, and "subtree" for trees).  The structural induction proof is a proof that the proposition holds for all the minimal structures and that if it holds for the immediate substructures of a certain structure  S, then it must hold for  S also. (Formally speaking, this then satisfies the premises of an axiom of well-founded induction, which asserts that these two conditions are sufficient for the proposition to hold for all x.)
A structurally recursive function uses the same idea to define a recursive function: "base cases" handle each minimal structure and a rule for recursion.  Structural recursion is usually proved correct by structural induction; in particularly easy cases, the inductive step is often left out.  The length and ++ functions in the example below are structurally recursive.
For example, if the structures are lists, one usually introduces the partial order "<", in which L < M whenever list L is the tail of list M.  Under this ordering, the empty list [] is the unique minimal element.  A structural induction proof of some proposition P(L) then consists of two parts:  A proof that P([]) is true and a proof that if P(L) is true for some list L, and if L is the tail of list M, then P(M) must also be true.
Eventually, there may exist more than one base case and/or more than one inductive case, depending on how the function or structure was constructed. In those cases, a structural induction proof of some proposition P(L) then consists of:

## Related

- [[Friedman's SSCG function]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Bunched logic]]
- [[Game semantics]]
- [[Kruskal's tree theorem]]
- [[Mathematical induction]]
- [[Mathematical proof]]
- [[Model theory]]
- [[Original proof of Gödel's completeness theorem]]
- [[Peano axioms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Structural_induction