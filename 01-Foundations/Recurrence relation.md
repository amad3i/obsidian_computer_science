---
title: "Recurrence relation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Recurrence_relation"
wikipedia_categories: ["Algebra", "Combinatorics", "Recurrence relations"]
related: ["[[Constant-recursive sequence]]", "[[Generalized arithmetic progression]]", "[[Series multisection]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algebraic signal processing]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]"]
---

# Recurrence relation

In mathematics and computer science, a recurrence relation is an equation according to which the 
  
    
      
        n
      
    
    
  
th term of a sequence of numbers is equal to some combination of the previous terms. Often, only 
  
    
      
        k
      
    
    
  
 previous terms of the sequence appear in the equation, for a parameter 
  
    
      
        k
      
    
    
  
 that is independent of 
  
    
      
        n
      
    
    
  
; this number 
  
    
      
        k
      
    
    
  
 is called the order of the relation. If the values of the first 
  
    
      
        k
      
    
    
  
 numbers in the sequence have been given, the rest of the sequence can be calculated by repeatedly applying the equation.
In linear recurrences, the nth term is equated to a linear function of the 
  
    
      
        k
      
    
    
  
 previous terms. A famous example is the recurrence for the Fibonacci numbers,

  
    
      
        
          F
          
            n
          
        
        
          F
          
            n
            1
          
        
        
          F
          
            n
            2
          
        
      
    
    
  

where the order 
  
    
      
        k
      
    
    
  
 is two and the linear function merely adds the two previous terms. This example is a linear recurrence with constant coefficients, because the coefficients of the linear function (1 and 1) are constants that do not depend on 
  
    
      
        n
        .
      
    
    
  
 For these recurrences, one can express the general term of the sequence as a closed-form expression of 
  
    
      
        n
      
    
    
  
. As well, linear recurrences with polynomial coefficients depending on 
  
    
      
        n
      
    
    
  
 are also important, because many common elementary functions and special functions have a Taylor series whose coefficients satisfy such a recurrence relation (see holonomic function).
Solving a recurrence relation means obtaining a closed-form solution: a non-recursive function of 
  
    
      
        n
      
    
    
  
.
The concept of a recurrence relation can be extended to multidimensional arrays, that is, indexed families that are indexed by tuples of natural numbers.

## Related

- [[Constant-recursive sequence]]
- [[Generalized arithmetic progression]]
- [[Series multisection]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algebraic signal processing]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Recurrence_relation