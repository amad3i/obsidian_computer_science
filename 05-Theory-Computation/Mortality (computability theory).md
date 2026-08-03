---
title: "Mortality (computability theory)"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Mortality_(computability_theory)"
wikipedia_categories: ["Computer science stubs", "Theory of computation", "Undecidable problems"]
related: ["[[Emptiness problem]]", "[[Entscheidungsproblem]]", "[[Halting problem]]", "[[List of undecidable problems]]", "[[Post correspondence problem]]", "[[Wang tile]]", "[[Ackermann function]]", "[[Admissible numbering]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]"]
---

# Mortality (computability theory)

In computability theory, the mortality problem is a decision problem related to the halting problem. For Turing machines, the halting problem can be stated as follows:
Given a Turing machine, and an input, decide whether the machine halts when run on the given input.
In contrast, the mortality problem for Turing machines asks whether all executions of the machine, starting from any configuration, halt. 
In the statement above, a configuration specifies both the machine's state (not necessarily its initial state),
its tape position and the contents of the tape. While we usually assume that in the starting configuration all but finitely many cells on the tape are blanks, in the mortality problem the tape can have arbitrary content, including infinitely many non-blank symbols written on it.
Philip K. Hooper proved in 1966 that the mortality problem is undecidable. This is true both for a machine with a tape infinite in both directions, and for a machine with semi-infinite tape. Note that this result does not directly follow from the well-known total function problem (Does a given machine halt for every input?), since the latter problem concerns only valid computations (starting with an initial configuration).
The variant in which only finite configurations are considered is also undecidable, as proved by Herman, who calls it ''the uniform halting problem''. He shows that the problem is not just undecidable, but 
  
    
      
        
          Π
          
            2
          
          
            0
          
        
      
    
    
  
-complete.

## Related

- [[Emptiness problem]]
- [[Entscheidungsproblem]]
- [[Halting problem]]
- [[List of undecidable problems]]
- [[Post correspondence problem]]
- [[Wang tile]]
- [[Ackermann function]]
- [[Admissible numbering]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mortality_(computability_theory)