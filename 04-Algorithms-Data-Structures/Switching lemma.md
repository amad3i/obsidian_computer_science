---
title: "Switching lemma"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Switching_lemma"
wikipedia_categories: ["Circuit complexity", "Computational complexity theory"]
related: ["[[Averaging argument]]", "[[Circuit complexity]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[BIT predicate]]"]
---

# Switching lemma

In computational complexity theory, Håstad's switching lemma is a key tool for proving lower bounds on the size of constant-depth Boolean circuits. It was first introduced by Johan Håstad to prove that AC0 Boolean circuits of depth k require size 
  
    
      
        exp
         
        Ω
        
          n
          
            1
            
              /
            
            k
            1
          
        
        )
      
    
    
  
 to compute the parity function on 
  
    
      
        n
      
    
    
  
 bits. He was later awarded the Gödel Prize for this work in 1994.
The switching lemma describes the behavior of a depth-2 circuit under random restriction, i.e. when randomly fixing most of the coordinates to 0 or 1. Specifically, from the lemma, it follows that a formula in conjunctive normal form (that is, an AND of ORs) becomes a formula in disjunctive normal form (an OR of ANDs) under random restriction, and vice versa. This "switching" gives the lemma its name.

## Related

- [[Averaging argument]]
- [[Circuit complexity]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[BIT predicate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Switching_lemma