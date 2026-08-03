---
title: "Inclusion–exclusion principle"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Inclusion–exclusion_principle"
wikipedia_categories: ["Abraham de Moivre", "Enumerative combinatorics", "Mathematical principles", "Probability theory"]
related: ["[[Addition principle]]", "[[Additive process]]", "[[Additive smoothing]]", "[[Almost surely]]", "[[Asymptotic geometry]]", "[[Big O in probability notation]]", "[[Blackwell-Girshick equation]]", "[[Blumenthal's zero–one law]]", "[[Brownian motion and Riemann zeta function]]", "[[Carleman's condition]]"]
---

# Inclusion–exclusion principle

In combinatorics, the inclusion–exclusion principle (Commonly referred to as PIE) is a counting technique which generalizes the familiar method of obtaining the number of elements in the union of two finite sets; symbolically expressed as

  
    
      
        
          |
        
        A
        ∪
        B
        
          |
        
        
          |
        
        A
        
          |
        
        
          |
        
        B
        
          |
        
        
          |
        
        A
        ∩
        B
        
          |
        
      
    
    
  

where A and B are two finite sets and |S| indicates the cardinality of a set S (which may be considered as the number of elements of the set, if the set is finite). The formula expresses the fact that the sum of the sizes of the two sets may be too large since some elements may be counted twice. The double-counted elements are those in the intersection of the two sets and the count is corrected by subtracting the size of the intersection.
The inclusion-exclusion principle, being a generalization of the two-set case, is perhaps more clearly seen in the case of three sets, which for the sets A, B and C is given by 

  
    
      
        
          |
        
        A
        ∪
        B
        ∪
        C
        
          |
        
        
          |
        
        A
        
          |
        
        
          |
        
        B
        
          |
        
        
          |
        
        C
        
          |
        
        
          |
        
        A
        ∩
        B
        
          |
        
        
          |
        
        A
        ∩
        C
        
          |
        
        
          |
        
        B
        ∩
        C
        
          |
        
        
          |
        
        A
        ∩
        B
        ∩
        C
        
          |
        
      
    
    
  

This formula can be verified by counting how many times each region in the Venn diagram figure is included in the right-hand side of the formula. In this case, when removing the contributions of over-counted elements, the number of elements in the mutual intersection of the three sets has been subtracted too often, so must be added back in to get the correct total.

Generalizing the results of these examples gives the principle of inclusion–exclusion.  To find the cardinality of the union of n sets:

Include the cardinalities of the sets.
Exclude the cardinalities of the pairwise intersections.
Include the cardinalities of the triple-wise intersections.
Exclude the cardinalities of the quadruple-wise intersections.
Include the cardinalities of the quintuple-wise intersections.
Continue, until the cardinality of the n-tuple-wise intersection is included (if n is odd) or excluded (n even).
The name comes from the idea that the principle is based on over-generous inclusion, followed by compensating exclusion.
This concept is attributed to Abraham de Moivre (1718), although it first appears in a paper of Daniel da Silva (1854) and later in a paper by J. J. Sylvester (1883). Sometimes the principle is referred to as the formula of Da Silva or Sylvester, due to these publications. The principle can be viewed as an example of the sieve method extensively used in number theory and is sometimes referred to as the sieve formula.
As finite probabilities are computed as counts relative to the cardinality of the probability space, the formulas for the principle of inclusion–exclusion remain valid when the cardinalities of the sets are replaced by finite probabilities. More generally, both versions of the principle can be put under the common umbrella of measure theory.
In a very abstract setting, the principle of inclusion–exclusion can be expressed as the calculation of the inverse of a certain matrix. This inverse has a special structure, making the principle an extremely valuable technique in combinatorics and related areas of mathematics. As Gian-Carlo Rota put it:

"One of the most useful principles of enumeration in discrete probability and combinatorial theory is the celebrated principle of inclusion–exclusion. When skillfully applied, this principle has yielded the solution to many a combinatorial problem."

## Related

- [[Addition principle]]
- [[Additive process]]
- [[Additive smoothing]]
- [[Almost surely]]
- [[Asymptotic geometry]]
- [[Big O in probability notation]]
- [[Blackwell-Girshick equation]]
- [[Blumenthal's zero–one law]]
- [[Brownian motion and Riemann zeta function]]
- [[Carleman's condition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Inclusion–exclusion_principle