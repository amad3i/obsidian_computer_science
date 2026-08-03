---
title: "Hamming ball"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hamming_ball"
wikipedia_categories: ["Coding theory", "Metric geometry", "String metrics"]
related: ["[[Hamming distance]]", "[[Lee distance]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]"]
---

# Hamming ball

In combinatorics, a Hamming ball is a metric ball for Hamming distance.
The Hamming ball of radius 
  
    
      
        r
      
    
    
  
 centered at a string 
  
    
      
        x
      
    
    
  
 over some alphabet (often the alphabet {0,1}) is the set of all strings of the same length that differ from 
  
    
      
        x
      
    
    
  
 in at most 
  
    
      
        r
      
    
    
  
 positions. This may be denoted using the standard notation for metric balls, 
  
    
      
        B
        x
        ,
        r
      
    
    
  
. For an alphabet 
  
    
      
        X
      
    
    
  
 and a string 
  
    
      
        x
      
    
    
  
, the Hamming ball is a subset of the Hamming space 
  
    
      
        
          X
          
            
              |
            
            x
            
              |
            
          
        
      
    
    
  
 of strings of the same length as 
  
    
      
        x
      
    
    
  
, and it is a proper subset whenever 
  
    
      
        r
        
          |
        
        x
        
          |
        
      
    
    
  
. The name Hamming ball comes from coding theory, where error correction codes can be defined as having disjoint Hamming balls around their codewords, and covering codes can be defined as having Hamming balls around the codeword whose union is the whole Hamming space.
Some local search algorithms for SAT solvers such as WalkSAT operate by using random guessing or covering codes to find a Hamming ball that contains a desired solution, and then searching within this Hamming ball to find the solution.
A version of Helly's theorem for Hamming balls is known: For Hamming balls of radius 
  
    
      
        r
      
    
    
  
 (in Hamming spaces of dimension greater than 
  
    
      
        r
      
    
    
  
), if a family of balls has the property that every subfamily of at most 
  
    
      
        
          2
          
            r
            1
          
        
      
    
    
  
 balls has a common intersection, then the whole family has a common intersection.

## Related

- [[Hamming distance]]
- [[Lee distance]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hamming_ball