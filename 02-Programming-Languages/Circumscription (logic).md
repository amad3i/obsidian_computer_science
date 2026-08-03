---
title: "Circumscription (logic)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Circumscription_(logic)"
wikipedia_categories: ["Logic programming", "Non-classical logic"]
related: ["[[Defeasible logic]]", "[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Clause (logic)]]", "[[Closed-world assumption]]"]
---

# Circumscription (logic)

Circumscription is a non-monotonic logic created by John McCarthy to formalize the common sense assumption that things are as expected unless otherwise specified. Circumscription was later used by McCarthy in an attempt to solve the frame problem. To implement circumscription in its initial formulation, McCarthy augmented first-order logic  to allow the minimization of the extension of some predicates, where the extension of a predicate is the set of tuples of values the predicate is true on. This minimization is similar to the closed-world assumption that what is not known to be true is false.
The original problem considered by McCarthy was that of missionaries and cannibals: there are three missionaries and three cannibals on one bank of a river; they have to cross the river using a boat that can only take two, with the additional constraint that cannibals must never outnumber the missionaries on either bank (as otherwise the missionaries would be killed and, presumably, eaten). The problem considered by McCarthy was not that of finding a sequence of steps to reach the goal (the article on the missionaries and cannibals problem contains one such solution), but rather that of excluding conditions that are not explicitly stated. For example, the solution "go half a mile south and cross the river on the bridge" is intuitively not valid because the statement of the problem does not mention such a bridge. On the other hand, the existence of this bridge is not excluded by the statement of the problem either. That the bridge does not exist is
a consequence of the implicit assumption that the statement of the problem contains everything that is relevant to its solution. Explicitly stating that a bridge does not exist is not a solution to this problem, as there are many other exceptional conditions that should be excluded (such as the presence of a rope for fastening the cannibals, the presence of a larger boat nearby, etc.)
Circumscription was later used by McCarthy to formalize the implicit assumption of inertia: things do not change unless otherwise specified.  Circumscription seemed to be useful to avoid specifying that conditions are not changed by all actions except those explicitly known to change them; this is known as the frame problem. However, the solution proposed by McCarthy was later shown to lead to wrong results in some cases, as in the Yale shooting problem scenario. Other solutions to the frame problem that correctly formalize the Yale shooting problem exist; some use circumscription but in a different way.

## Related

- [[Defeasible logic]]
- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Clause (logic)]]
- [[Closed-world assumption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Circumscription_(logic)