---
title: "Structured program theorem"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Structured_program_theorem"
wikipedia_categories: ["Models of computation", "Programming language theory", "Theorems in computational complexity theory"]
related: ["[[Abstract machine]]", "[[Abstract state machine]]", "[[Abstract syntax]]", "[[Algorithm characterizations]]", "[[Applicative computing systems]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Bulk synchronous parallel]]", "[[CIP-Tool]]", "[[Communicating X-machine]]", "[[Complexity and Real Computation]]"]
---

# Structured program theorem

In programming language theory, the structured program theorem, generally called the Böhm–Jacopini theorem, states that a class of control-flow graphs (historically called flowcharts in this context) can compute any computable function using only the following three control structures to combine subprograms (statements and blocks):

Sequence
Executing one subprogram, and then another subprogram
Selection
Executing one of two subprograms according to the value of a boolean expression
Iteration
Repeatedly executing a subprogram as long as a boolean expression is true
More precise definitions are listed in the next section.
The structured chart subject to these constraints, particularly the loop constraint implying a single exit (as described later in this article), may however use additional variables in the form of bits (stored in an extra integer variable in the original proof) in order to keep track of information that the original program represents by the program location. The construction was based on Böhm's programming language P′′.
The theorem forms the basis of structured programming, a programming paradigm which eschews the goto statement, exclusively using other control semantics for selection and iteration.

## Related

- [[Abstract machine]]
- [[Abstract state machine]]
- [[Abstract syntax]]
- [[Algorithm characterizations]]
- [[Applicative computing systems]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[Bulk synchronous parallel]]
- [[CIP-Tool]]
- [[Communicating X-machine]]
- [[Complexity and Real Computation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Structured_program_theorem