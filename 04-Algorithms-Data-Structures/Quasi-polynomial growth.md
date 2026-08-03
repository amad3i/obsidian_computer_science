---
title: "Quasi-polynomial growth"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Quasi-polynomial_growth"
wikipedia_categories: ["Asymptotic analysis", "Computational complexity theory"]
related: ["[[L-notation]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Big O notation]]"]
---

# Quasi-polynomial growth

In theoretical computer science, a function 
  
    
      
        f
        n
      
    
    
  
 is said to exhibit quasi-polynomial growth when it has an upper bound of the form

  
    
      
        f
        n
        =
        
          2
          
            O
            
              
              
            
            log
             
            n
            
              
                c
              
            
            
              
              
            
          
        
      
    
    
  

for some constant 
  
    
      
        c
      
    
    
  
, as expressed using big O notation. That is, it is bounded by an exponential function of a polylogarithmic function. This generalizes the polynomials and the functions of polynomial growth, for which one can take 
  
    
      
        c
        1
      
    
    
  
. A function with quasi-polynomial growth is also said to be quasi-polynomially bounded.
Quasi-polynomial growth has been used in the analysis of algorithms to describe certain algorithms whose computational complexity is not polynomial, but is substantially smaller than exponential. In particular, algorithms whose worst-case running times exhibit quasi-polynomial growth are said to take quasi-polynomial time. As well as time complexity, some algorithms require quasi-polynomial space complexity, use a quasi-polynomial number of parallel processors, can be expressed as algebraic formulas of quasi-polynomial size or have a quasi-polynomial competitive ratio. In some other cases, quasi-polynomial growth is used to model restrictions on the inputs to a problem that, when present, lead to good performance from algorithms on those inputs. It can also bound the size of the output for some problems; for instance, for the shortest path problem with linearly varying edge weights, the number of distinct solutions can be quasipolynomial.
Beyond theoretical computer science, quasi-polynomial growth bounds have also been used in mathematics, for instance in partial results on the Hirsch conjecture for the diameter of polytopes in polyhedral combinatorics, or relating the sizes of cliques and independent sets in certain classes of graphs. However, in polyhedral combinatorics and enumerative combinatorics, a different meaning of the same word also is used, for the quasi-polynomials, functions that generalize polynomials by having periodic coefficients.

## Related

- [[L-notation]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[Big O notation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quasi-polynomial_growth