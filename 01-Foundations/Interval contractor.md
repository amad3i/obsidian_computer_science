---
title: "Interval contractor"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Interval_contractor"
wikipedia_categories: ["Arithmetic", "Computer arithmetic", "Numerical analysis", "Optimization algorithms and methods"]
related: ["[[Interval arithmetic]]", "[[2Sum]]", "[[CORDIC]]", "[[False precision]]", "[[Gal's accurate tables]]", "[[Grossone]]", "[[INTLAB]]", "[[Kahan summation algorithm]]", "[[Kantorovich theorem]]", "[[Karlsruhe Accurate Arithmetic]]"]
---

# Interval contractor

In mathematics, an interval contractor (or contractor for short) associated to a set 
  
    
      
        X
      
    
    
  
 is  an operator 
  
    
      
        C
      
    
    
  
 which associates to a hyperrectangle 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        
          
            
              R
            
          
          
            n
          
        
      
    
    
  
 another box 
  
    
      
        C
        [
        x
        )
      
    
    
  
 of 
  
    
      
        
          
            
              R
            
          
          
            n
          
        
      
    
    
  
  such that the two following properties are always satisfied:

  
    
      
        C
        [
        x
        )
        ⊂
        x
      
    
    
  
 (contractance property)

  
    
      
        C
        [
        x
        )
        ∩
        X
        [
        x
        ∩
        X
      
    
    
  
 (completeness property)
A contractor associated to a constraint (such as an equation or an inequality) is a 
contractor associated to the set 
  
    
      
        X
      
    
    
  
 of all 
  
    
      
        x
      
    
    
  
 which satisfy the constraint.  
Contractors make it possible to improve the efficiency of branch-and-bound algorithms classically used in interval analysis.

## Related

- [[Interval arithmetic]]
- [[2Sum]]
- [[CORDIC]]
- [[False precision]]
- [[Gal's accurate tables]]
- [[Grossone]]
- [[INTLAB]]
- [[Kahan summation algorithm]]
- [[Kantorovich theorem]]
- [[Karlsruhe Accurate Arithmetic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interval_contractor