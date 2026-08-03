---
title: "Existential theory of the reals"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Existential_theory_of_the_reals"
wikipedia_categories: ["Computational complexity theory", "Formal theories of arithmetic", "Real algebraic geometry"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Boolean circuit]]", "[[Büchi arithmetic]]"]
---

# Existential theory of the reals

In mathematical logic, computational complexity theory, and computer science, the existential theory of the reals is the set of all true sentences of the form

  
    
      
        ∃
        
          X
          
            1
          
        
        ⋯
        ∃
        
          X
          
            n
          
        
        
        F
        
          X
          
            1
          
        
        ,
        …
        ,
        
          X
          
            n
          
        
        ,
      
    
    
  

where the variables 
  
    
      
        
          X
          
            i
          
        
      
    
    
  
 are interpreted as having real number values, and where 
  
    
      
        F
        
          X
          
            1
          
        
        ,
        …
        
          X
          
            n
          
        
      
    
    
  
 is a quantifier-free formula involving equalities and inequalities of real polynomials. A sentence of this form is true if it is possible to find values for all of the variables that, when substituted into formula 
  
    
      
        F
      
    
    
  
, make it become true.
The decision problem for the existential theory of the reals is the problem of finding an algorithm that decides, for each such sentence, whether it is true or false. Equivalently, it is the problem of testing whether a given semialgebraic set is non-empty. This decision problem is NP-hard and lies in PSPACE, giving it significantly lower complexity than Alfred Tarski's quantifier elimination procedure for deciding statements in the first-order theory of the reals without the restriction to existential quantifiers. However, in practice, general methods for the first-order theory remain the preferred choice for solving these problems.
The complexity class 
  
    
      
        ∃
        
          R
        
      
    
    
  
 has been defined to describe the class of computational problems that may be translated into equivalent sentences of this form. In structural complexity theory, it lies between NP and PSPACE. Many natural problems in geometric graph theory, especially problems of recognizing geometric intersection graphs and straightening the edges of graph drawings with crossings, belong to 
  
    
      
        ∃
        
          R
        
      
    
    
  
, and are complete for this class. Here, completeness means that there exists a translation in the reverse direction, from an arbitrary sentence over the reals into an equivalent instance of the given problem.

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[Boolean circuit]]
- [[Büchi arithmetic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Existential_theory_of_the_reals