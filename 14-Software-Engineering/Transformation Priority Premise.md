---
title: "Transformation Priority Premise"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Transformation_Priority_Premise"
wikipedia_categories: ["Extreme programming", "Software development philosophies", "Software development process", "Software testing"]
related: ["[[Continuous test-driven development]]", "[[Test-driven development]]", "[[Acceptance test-driven development]]", "[[Classification Tree Method]]", "[[Continuous integration]]", "[[Daily build]]", "[[Door problem]]", "[[Dynamic testing]]", "[[Extreme programming]]", "[[Extreme programming practices]]"]
---

# Transformation Priority Premise

Transformation Priority Premise (TPP) is a programming approach developed by Robert C. Martin (Uncle Bob) as a refinement to make the process of test-driven development (TDD) easier and more effective for a computer programmer.
Transformation Priority Premise states that simpler transformations should be preferred:

[...]Refactorings have counterparts called Transformations. Refactorings are simple operations that change the structure of code without changing its behavior. Transformations are simple operations that change the behavior of code. Transformations can be used as the sole means for passing the currently failing test in the red/green/refactor cycle. Transformations have a priority, or a preferred ordering, which if maintained, by the ordering of the tests, will prevent impasses, or long outages in the red/green/refactor cycle.
This approach facilitates the programmer doing the simplest possible thing for the purposes of test-driven development as they can explicitly refer to the list of transformations and favor the simpler transformations (from the top of the list) over those further down in the list in the first instance.

 The Transformation Priority Premise is a name given to the mental structure TDD’ers build up over time as to balance your code from being too specific, rather than generic. The idea is that with each example you add to the tests you move up the Transformation Priority list, making your code more generic, so able to handle more of the cases. In contrast, your tests, with more examples, become ever more specific and focused on the problem. So you start with a constant for your first test, for your next test you might change that constant to an “if” for the next step you might introduce a loop. Each time you’re moving up the priority premise. The aim of following this structure is to avoid Accidental Complication, and to add only to Essential Complication. Each step is the smallest possible change you can make to implement only the code required to implement the examples given in the test..

## Related

- [[Continuous test-driven development]]
- [[Test-driven development]]
- [[Acceptance test-driven development]]
- [[Classification Tree Method]]
- [[Continuous integration]]
- [[Daily build]]
- [[Door problem]]
- [[Dynamic testing]]
- [[Extreme programming]]
- [[Extreme programming practices]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transformation_Priority_Premise