---
title: "Genetic programming"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Genetic_programming"
wikipedia_categories: ["Genetic programming"]
related: ["[[Gene expression programming]]", "[[Grammar induction]]", "[[Grammatical evolution]]", "[[Linear genetic programming]]", "[[Multi expression programming]]", "[[Parity benchmark]]", "[[Santa Fe Trail problem]]", "[[Symbolic regression]]"]
---

# Genetic programming

Genetic programming (GP) is an evolutionary algorithm, an artificial intelligence technique mimicking natural evolution, which operates on a population of programs. It applies the genetic operators selection according to a predefined fitness measure, mutation and crossover.  
The crossover operation involves swapping specified parts of selected pairs (parents) to produce new and different offspring that become part of the new generation of programs. Some programs not selected for reproduction are copied from the current generation to the new generation. Mutation involves substitution of some random part of a program with some other random part of a program. Then the selection and other operations are recursively applied to the new generation of programs.
Typically, members of each new generation are on average more fit than the members of the previous generation, and the best-of-generation program is often better than the best-of-generation programs from previous generations.  Termination of the evolution usually occurs when some individual program reaches a predefined proficiency or fitness level.
It may and often does happen that a particular run of the algorithm results in premature convergence to some local maximum that is not a globally optimal or even good solution.  Multiple runs (dozens to hundreds) are usually necessary to produce a very good result.  It may also be necessary to have a large starting population size and variability of the individuals to avoid pathologies.

## Related

- [[Gene expression programming]]
- [[Grammar induction]]
- [[Grammatical evolution]]
- [[Linear genetic programming]]
- [[Multi expression programming]]
- [[Parity benchmark]]
- [[Santa Fe Trail problem]]
- [[Symbolic regression]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Genetic_programming