---
title: "Erdős–Graham problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Erdős–Graham_problem"
wikipedia_categories: ["Combinatorics", "Conjectures that have been proved", "Egyptian fractions", "Paul Erdős", "Theorems in number theory"]
related: ["[[Cameron–Erdős conjecture]]", "[[Dinitz theorem]]", "[[Kemnitz's conjecture]]", "[[Toida's conjecture]]", "[[Zero-sum problem]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]"]
---

# Erdős–Graham problem

In combinatorial number theory, the Erdős–Graham problem is the problem of proving that, if the set 
  
    
      
        2
        ,
        3
        ,
        4
        ,
        …
      
    
    
  
 of integers greater than one is partitioned into finitely many subsets, then one of the subsets can be used to form an Egyptian fraction representation of unity. That is, for every 
  
    
      
        r
        0
      
    
    
  
, and every 
  
    
      
        r
      
    
    
  
-coloring of the integers greater than one, there is a finite monochromatic subset 
  
    
      
        S
      
    
    
  
 of these integers such that.

  
    
      
        
          ∑
          
            n
            ∈
            S
          
        
        
          
            1
            n
          
        
        1.
      
    
    
  

In more detail, Paul Erdős and Ronald Graham conjectured that, for sufficiently large 
  
    
      
        r
      
    
    
  
, the largest member of 
  
    
      
        S
      
    
    
  
 could be bounded by 
  
    
      
        
          b
          
            r
          
        
      
    
    
  
 for some constant 
  
    
      
        b
      
    
    
  
 independent of 
  
    
      
        r
      
    
    
  
. It was known that, for this to be true, 
  
    
      
        b
      
    
    
  
 must be at least Euler's constant 
  
    
      
        e
      
    
    
  
.
Ernie Croot proved the conjecture as part of his Ph.D. thesis, and later (while a post-doctoral researcher at UC Berkeley) published the proof in the Annals of Mathematics. The value Croot gives for 
  
    
      
        b
      
    
    
  
 is very large: it is at most 
  
    
      
        
          e
          
            167000
          
        
      
    
    
  
. Croot's result follows as a corollary of a more general theorem stating the existence of Egyptian fraction representations of unity for sets 
  
    
      
        C
      
    
    
  
 of smooth numbers in intervals of the form 
  
    
      
        X
        ,
        
          X
          
            1
            δ
          
        
      
    
    
  
, where 
  
    
      
        C
      
    
    
  
 contains sufficiently many numbers so that the sum of their reciprocals is at least six. The Erdős–Graham conjecture follows from this result by showing that one can find an interval of this form in which the sum of the reciprocals of all smooth numbers is at least 
  
    
      
        6
        r
      
    
    
  
; therefore, if the integers are 
  
    
      
        r
      
    
    
  
-colored there must be a monochromatic subset 
  
    
      
        C
      
    
    
  
 satisfying the conditions of Croot's theorem.
A stronger form of the result, that any set of integers with positive upper density includes the denominators of an Egyptian fraction representation of one, was announced in 2021 by Thomas Bloom, a postdoctoral researcher at the University of Oxford.

## Related

- [[Cameron–Erdős conjecture]]
- [[Dinitz theorem]]
- [[Kemnitz's conjecture]]
- [[Toida's conjecture]]
- [[Zero-sum problem]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Erdős–Graham_problem