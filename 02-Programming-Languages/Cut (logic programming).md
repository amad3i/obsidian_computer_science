---
title: "Cut (logic programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Cut_(logic_programming)"
wikipedia_categories: ["Logic programming"]
related: ["[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Circumscription (logic)]]", "[[Clause (logic)]]", "[[Closed-world assumption]]"]
---

# Cut (logic programming)

The cut, in Prolog, is a goal, written as !, which always succeeds but cannot be backtracked. Cuts can prevent unwanted backtracking, which could add unwanted solutions and/or space/time overhead to a query.
The cut should be used sparingly. While cuts can be inserted into code containing errors, if a test is unnecessary because a cut has guaranteed that it is true, it is good practice to say so in a comment at the appropriate place.
Some programmers call the cut a controversial control facility because it was added for efficiency reasons only and is not a logical formula.

## Related

- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Circumscription (logic)]]
- [[Clause (logic)]]
- [[Closed-world assumption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cut_(logic_programming)