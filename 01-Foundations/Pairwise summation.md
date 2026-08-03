---
title: "Pairwise summation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Pairwise_summation"
wikipedia_categories: ["Computer arithmetic", "Numerical analysis"]
related: ["[[2Sum]]", "[[CORDIC]]", "[[Gal's accurate tables]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[INTLAB]]", "[[Kahan summation algorithm]]", "[[Karlsruhe Accurate Arithmetic]]", "[[Numerical error]]", "[[Sterbenz lemma]]"]
---

# Pairwise summation

In numerical analysis, pairwise summation, also called cascade summation, is a summation algorithm, i.e. a technique to sum a sequence of finite-precision floating-point numbers that substantially reduces the accumulated round-off error compared to naively accumulating the sum in sequence.  Although there are other techniques such as Kahan summation that typically have even smaller round-off errors, pairwise summation is nearly as good (differing only by a logarithmic factor) while having much lower computational cost—it can be implemented so as to have nearly the same cost (and exactly the same number of arithmetic operations) as naive summation.
In particular, pairwise summation of a sequence of n numbers xn works by recursively breaking the sequence into two halves, summing each half, and adding the two sums: a divide and conquer algorithm.  Its worst-case roundoff errors grow asymptotically as at most O(ε log n), where ε is the machine precision (assuming a fixed condition number, as discussed below).  In comparison, the naive technique of accumulating the sum in sequence (adding each xi one at a time for i = 1, ..., n) has roundoff errors that grow at worst as O(εn).  Kahan summation has a worst-case error of roughly O(ε), independent of n, but requires several times more arithmetic operations.   If the roundoff errors are random, and in particular have random signs, then they form a random walk and the error growth is reduced to an average of 
  
    
      
        O
        ε
        
          
             
            n
          
        
      
    
    
  
 for pairwise summation.
A very similar recursive structure of DFT decomposition is found in many fast Fourier transform (FFT) algorithms, and is responsible for the same slow roundoff accumulation of those FFTs when implemented with a breadth-first technique due to poor memory locality.

## Related

- [[2Sum]]
- [[CORDIC]]
- [[Gal's accurate tables]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[INTLAB]]
- [[Kahan summation algorithm]]
- [[Karlsruhe Accurate Arithmetic]]
- [[Numerical error]]
- [[Sterbenz lemma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pairwise_summation