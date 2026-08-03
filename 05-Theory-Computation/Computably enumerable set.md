---
title: "Computably enumerable set"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Computably_enumerable_set"
wikipedia_categories: ["Computability theory", "Theory of computation"]
related: ["[[Ackermann function]]", "[[Admissible numbering]]", "[[Busy beaver]]", "[[Chain rule for Kolmogorov complexity]]", "[[Church–Turing thesis]]", "[[Church–Turing–Deutsch principle]]", "[[Computability]]", "[[Computable function]]", "[[Computable number]]", "[[Computable set]]"]
---

# Computably enumerable set

In computability theory, a set S of natural numbers is called computably enumerable (c.e.), recursively enumerable (r.e.), semidecidable, partially decidable, listable, provable or Turing-recognizable if:

There is an algorithm such that the set of input numbers for which the algorithm halts is exactly S.
Or, equivalently,

There is an algorithm that enumerates the members of S.  That means that its output is a list of all the members of S:  s1, s2, s3, ... .  If S is infinite, this algorithm will run forever, but each element of S will be returned after a finite amount of time. Note that these elements do not have to be listed in a particular way, say from smallest to largest.
The first condition suggests why the term semidecidable is sometimes used. More precisely, if a number is in the set, one can decide this by running the algorithm, but if the number is not in the set, the algorithm can run forever, and no information is returned. A set that is "completely decidable" is a computable set.  The second condition suggests why computably enumerable is used. The abbreviations c.e. and r.e. are often used, even in print, instead of the full phrase.
In computational complexity theory, the complexity class containing all computably enumerable sets is RE. In recursion theory, the lattice of c.e. sets under inclusion is denoted 
  
    
      
        
          
            E
          
        
      
    
    
  
.

## Related

- [[Ackermann function]]
- [[Admissible numbering]]
- [[Busy beaver]]
- [[Chain rule for Kolmogorov complexity]]
- [[Church–Turing thesis]]
- [[Church–Turing–Deutsch principle]]
- [[Computability]]
- [[Computable function]]
- [[Computable number]]
- [[Computable set]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computably_enumerable_set