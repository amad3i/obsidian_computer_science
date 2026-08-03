---
title: "Programming by permutation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Programming_by_permutation"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Programming by permutation

Programming by permutation, sometimes called "programming by accident" or "shotgunning", is an approach to software development wherein a programming problem is solved by iteratively making small changes (permutations) and testing each change to see if it behaves as desired. This approach sometimes seems attractive when the programmer does not fully understand the code and believes that one or more small modifications may result in code that is correct.
This tactic is not productive when:

There is lack of easily executed automated regression tests with significant coverage of the codebase:
a series of small modifications can easily introduce new undetected bugs into the code, leading to a "solution" that is even less correct than the starting point
Without test-driven development it is rarely possible to measure, by empirical testing, whether the solution will work for all or significant part of the relevant cases
No version control system is used (for example Git, Mercurial or Subversion) or it is not used during iterations to reset the situation when a change has no visible effect
many false starts and corrections usually occur before a satisfactory endpoint is reached
in the worst case, the original state of the code may be irretrievably lost
Programming by permutation gives little or no assurance about the quality of the code produced—it is the polar opposite of formal verification.
Programmers are often compelled to program by permutation when an API is insufficiently documented. This lack of clarity drives others to copy and paste from reference code which is assumed to be correct, but was itself written as a result of programming by permutation.
In some cases where the programmer can logically explain that exactly one out of a small set of variations must work, programming by permutation leads to correct code (which then can be verified) and makes it unnecessary to think about the other (wrong) variations.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Programming_by_permutation