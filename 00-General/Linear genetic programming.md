---
title: "Linear genetic programming"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Linear_genetic_programming"
wikipedia_categories: ["Genetic programming"]
related: ["[[Gene expression programming]]", "[[Genetic programming]]", "[[Grammar induction]]", "[[Grammatical evolution]]", "[[Multi expression programming]]", "[[Parity benchmark]]", "[[Santa Fe Trail problem]]", "[[Symbolic regression]]"]
---

# Linear genetic programming

"Linear genetic programming" is unrelated to "linear programming".
Linear genetic programming (LGP) is a particular method of genetic programming wherein computer programs in a population are represented as a sequence of register-based instructions from an imperative programming language or machine language. The adjective "linear" stems from the fact that each LGP program is a sequence of instructions and the sequence of instructions is normally executed sequentially. Like in other programs, the data flow in LGP can be modeled as a graph that will visualize the potential multiple usage of register contents and the existence of structurally noneffective code (introns) which are two main differences of this genetic representation from the more common tree-based genetic programming (TGP) variant.

Like other Genetic Programming methods, Linear genetic programming requires the input of data to run the program population on. Then, the output of the program (its behaviour) is judged against some target behaviour, using a fitness function. However, LGP is generally more efficient than tree genetic programming due to its two main differences mentioned above: Intermediate results (stored in registers) can be reused and a simple intron removal algorithm exists that can be executed to remove all non-effective code prior to programs being run on the intended data. These two differences  often result in compact solutions and substantial computational savings compared to the highly constrained data flow in trees and the common method of executing all tree nodes in TGP. Furthermore, LGP naturally has multiple outputs by defining multiple output registers and easily cooperates with control flow operations.
Linear genetic programming has been applied in many domains, including system modeling and system control with considerable success.
Linear genetic programming should not be confused with linear tree programs in tree genetic programming, program composed of a variable number of unary functions and a single terminal. Note that linear tree GP differs from bit string genetic algorithms since a population may contain programs of different lengths and there may be more than two types of functions or more than two types of terminals.

## Related

- [[Gene expression programming]]
- [[Genetic programming]]
- [[Grammar induction]]
- [[Grammatical evolution]]
- [[Multi expression programming]]
- [[Parity benchmark]]
- [[Santa Fe Trail problem]]
- [[Symbolic regression]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_genetic_programming