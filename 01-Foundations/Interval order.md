---
title: "Interval order"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Interval_order"
wikipedia_categories: ["Combinatorics", "Order theory"]
related: ["[[Cyclic order]]", "[[Inversion (discrete mathematics)]]", "[[Lubell–Yamamoto–Meshalkin inequality]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]"]
---

# Interval order

In mathematics, especially order theory,
the interval order for a collection of intervals on the real line
is the partial order corresponding to their left-to-right precedence relation—one interval, I1, being considered less than another, I2, if I1 is completely to the left of I2.
More formally, a countable poset 
  
    
      
        P
        (
        X
        ,
        ≤
      
    
    
  
 is an interval order if and only if
there exists a bijection from 
  
    
      
        X
      
    
    
  
 to a set of real intervals,
so 
  
    
      
        
          x
          
            i
          
        
        ↦
        
          ℓ
          
            i
          
        
        ,
        
          r
          
            i
          
        
      
    
    
  
,
such that for any 
  
    
      
        
          x
          
            i
          
        
        ,
        
          x
          
            j
          
        
        ∈
        X
      
    
    
  
 we have

  
    
      
        
          x
          
            i
          
        
        
          x
          
            j
          
        
      
    
    
  
 in 
  
    
      
        P
      
    
    
  
 exactly when 
  
    
      
        
          r
          
            i
          
        
        
          ℓ
          
            j
          
        
      
    
    
  
.
Such posets may be equivalently
characterized as those with no induced subposet isomorphic to the
pair of two-element chains, in other words as the 
  
    
      
        2
        2
      
    
    
  
-free posets. Fully written out, this means that for any two pairs of elements 
  
    
      
        a
        b
      
    
    
  
 and 
  
    
      
        c
        d
      
    
    
  
 one must have 
  
    
      
        a
        d
      
    
    
  
 or 
  
    
      
        c
        b
      
    
    
  
.
The subclass of interval orders obtained by restricting the intervals to those of unit length, so they all have the form 
  
    
      
        
          ℓ
          
            i
          
        
        ,
        
          ℓ
          
            i
          
        
        1
      
    
    
  
, is precisely the semiorders.
The complement of the comparability graph of an interval order (
  
    
      
        X
      
    
    
  
, ≤)
is the interval graph 
  
    
      
        X
        ,
        ∩
      
    
    
  
.
Interval orders should not be confused with the interval-containment orders, which are the inclusion orders on intervals on the real line (equivalently, the orders of dimension ≤ 2).
Interval orders' practical applications include modelling evolution of species and archeological histories of pottery styles.

## Related

- [[Cyclic order]]
- [[Inversion (discrete mathematics)]]
- [[Lubell–Yamamoto–Meshalkin inequality]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interval_order