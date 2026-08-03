---
title: "Short integer solution problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Short_integer_solution_problem"
wikipedia_categories: ["Computational hardness assumptions", "Computational problems", "Lattice-based cryptography", "Number theory", "Post-quantum cryptography"]
related: ["[[Ideal lattice]]", "[[Lattice reduction]]", "[[Ring learning with errors key exchange]]", "[[3x + 1 semigroup]]", "[[Abc conjecture]]", "[[Abel's summation formula]]", "[[AI-complete]]", "[[Algebraic number theory]]", "[[Amenable number]]", "[[Amicable triple]]"]
---

# Short integer solution problem

Short integer solution (SIS) and ring-SIS problems are two average-case problems that are used in lattice-based cryptography constructions. Lattice-based cryptography began in 1996 from a seminal work by Miklós Ajtai who presented a family of one-way functions based on SIS problem. He showed that it is secure in an average case if the shortest vector problem 
  
    
      
        
          
            S
            V
            P
          
          
            γ
          
        
      
    
    
  
 (where 
  
    
      
        γ
        
          n
          
            c
          
        
      
    
    
  
 for some constant 
  
    
      
        c
        0
      
    
    
  
) is hard in the worst case.
Average case problems are the problems that are hard to be solved for some randomly selected instances. For cryptography applications, worst case complexity is not sufficient, and we need to guarantee cryptographic construction are hard based on average case complexity.

## Related

- [[Ideal lattice]]
- [[Lattice reduction]]
- [[Ring learning with errors key exchange]]
- [[3x + 1 semigroup]]
- [[Abc conjecture]]
- [[Abel's summation formula]]
- [[AI-complete]]
- [[Algebraic number theory]]
- [[Amenable number]]
- [[Amicable triple]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Short_integer_solution_problem