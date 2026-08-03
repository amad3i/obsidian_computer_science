---
title: "Counterexample-guided abstraction refinement"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Counterexample-guided_abstraction_refinement"
wikipedia_categories: ["Logical calculi", "Modal logic", "Model checking"]
related: ["[[Modal μ-calculus]]", "[[Abstract model checking]]", "[[Agentive logic]]", "[[Alternating timed automaton]]", "[[Binary decision diagram]]", "[[Büchi automaton]]", "[[Clock (model checking)]]", "[[Dynamic logic (modal logic)]]", "[[Epistemic modal logic]]", "[[Event calculus]]"]
---

# Counterexample-guided abstraction refinement

Counterexample-guided abstraction refinement (CEGAR) is a technique for symbolic model checking. It is also applied in modal logic tableau calculi algorithms to optimise their efficiency.
In computer-aided verification and analysis of programs, models of computation often consist of states. Models for even small programs, however, may have an enormous number of states. This is identified as the state explosion problem. CEGAR addresses this problem with two stages — abstraction, which simplifies a model by grouping states, and refinement, which increases the precision of the abstraction to better approximate the original model.
If a desired property for a program is not satisfied in the abstract model, a counterexample is generated. The CEGAR process then checks whether the counterexample is spurious, i.e., if the counterexample also applies to the under-abstraction but not the actual program. If this is the case, it concludes that the counterexample is attributed to inadequate precision of the abstraction. Otherwise, the process finds a bug in the program. Refinement is performed when a counterexample is found to be spurious. The iterative procedure terminates either if a bug is found or when the abstraction has been refined to the extent that it is equivalent to the original model.

## Related

- [[Modal μ-calculus]]
- [[Abstract model checking]]
- [[Agentive logic]]
- [[Alternating timed automaton]]
- [[Binary decision diagram]]
- [[Büchi automaton]]
- [[Clock (model checking)]]
- [[Dynamic logic (modal logic)]]
- [[Epistemic modal logic]]
- [[Event calculus]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Counterexample-guided_abstraction_refinement