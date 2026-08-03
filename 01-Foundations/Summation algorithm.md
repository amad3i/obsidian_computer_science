---
title: "Summation algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Summation_algorithm"
wikipedia_categories: ["Computer arithmetic", "Floating point", "Numerical analysis"]
related: ["[[2Sum]]", "[[Kahan summation algorithm]]", "[[Sterbenz lemma]]", "[[CORDIC]]", "[[Gal's accurate tables]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[INTLAB]]", "[[Karlsruhe Accurate Arithmetic]]", "[[Numerical error]]"]
---

# Summation algorithm

A summation algorithm is an algorithm that computes the sum of a finite list of numbers 
  
    
      
        ∑
        L
        i
      
    
    {\textstyle \sum L[i]}
  
. It is especially relevant in floating-point arithmetic where the associative property 
  
    
      
        a
        b
        +
        c
        a
        (
        b
        c
      
    
    
  
 does not hold like it does in (mathematical) real numbers, rational numbers, fixed-point numbers, and unsigned integers, so that the order of calculation can affect the final result. A closely related problem is the calculation of dot products, both of which have numerous proposed algorithms that differ in terms of simplicity, speed (single-thread and parallelized), and accuracy..

## Related

- [[2Sum]]
- [[Kahan summation algorithm]]
- [[Sterbenz lemma]]
- [[CORDIC]]
- [[Gal's accurate tables]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[INTLAB]]
- [[Karlsruhe Accurate Arithmetic]]
- [[Numerical error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Summation_algorithm