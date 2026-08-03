---
title: "Computation tree logic"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Computation_tree_logic"
wikipedia_categories: ["Automata (computation)", "Logic in computer science", "Temporal logic"]
related: ["[[Alternating-time temporal logic]]", "[[CTL-]]", "[[Linear temporal logic to Büchi automaton]]", "[[Sequential logic]]", "[[Star-free language]]", "[[1-in-3-SAT]]", "[[Abstract machine]]", "[[Abstract rewriting system]]", "[[ACM Transactions on Computational Logic]]", "[[Agent verification]]"]
---

# Computation tree logic

Computation tree logic (CTL) is a branching-time logic, meaning that its model of time is a tree-like structure in which the future is not determined; there are different paths in the future, any one of which might be an actual path that is realized. It is used in formal verification of software or hardware artifacts, typically by software applications known as model checkers, which determine if a given artifact possesses safety or liveness properties. For example, CTL can specify that when some initial condition is satisfied (e.g., all program variables are positive or no cars on a highway straddle two lanes), then all possible executions of a program avoid some undesirable condition (e.g., dividing a number by zero or two cars colliding on a highway). In this example, the safety property could be verified by a model checker that explores all possible transitions out of program states satisfying the initial condition and ensures that all such executions satisfy the property. Computation tree logic belongs to a class of temporal logics that includes linear temporal logic (LTL). Although there are properties expressible only in CTL and properties expressible only in LTL, all properties expressible in either logic can also be expressed in CTL*.

## Related

- [[Alternating-time temporal logic]]
- [[CTL-]]
- [[Linear temporal logic to Büchi automaton]]
- [[Sequential logic]]
- [[Star-free language]]
- [[1-in-3-SAT]]
- [[Abstract machine]]
- [[Abstract rewriting system]]
- [[ACM Transactions on Computational Logic]]
- [[Agent verification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computation_tree_logic