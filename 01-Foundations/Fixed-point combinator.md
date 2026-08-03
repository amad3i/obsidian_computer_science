---
title: "Fixed-point combinator"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Fixed-point_combinator"
wikipedia_categories: ["Combinatory logic", "Fixed points (mathematics)", "Lambda calculus", "Mathematics of computing", "Programming language comparisons", "Recursion"]
related: ["[[Applicative computing systems]]", "[[B, C, K, W system]]", "[[Combinatory logic]]", "[[Higher-order function]]", "[[Lambda calculus]]", "[[Lambda lifting]]", "[[SKI combinator calculus]]", "[[Actor model theory]]", "[[Anonymous function]]", "[[Beta normal form]]"]
---

# Fixed-point combinator

In combinatory logic for computer science, a fixed-point combinator (or fixpoint combinator) is a higher-order function (i.e., a function that takes a function as argument) that returns some fixed point (a value that is mapped to itself) of its argument function, if one exists.
Formally, if 
  
    
      
        
          f
          i
          x
        
      
    
    
  
 is a fixed-point combinator and the function 
  
    
      
        f
      
    
    
  
 has one or more fixed points, then 
  
    
      
        
          f
          i
          x
        
         
        f
      
    
    
  
 is one of these fixed points, i.e.,

  
    
      
        
          f
          i
          x
        
         
        f
         
        f
         
        
          f
          i
          x
        
         
        f
        .
      
    
    
  

Fixed-point combinators can be defined in the lambda calculus and in functional programming languages, and provide a means to allow for recursive definitions.

## Related

- [[Applicative computing systems]]
- [[B, C, K, W system]]
- [[Combinatory logic]]
- [[Higher-order function]]
- [[Lambda calculus]]
- [[Lambda lifting]]
- [[SKI combinator calculus]]
- [[Actor model theory]]
- [[Anonymous function]]
- [[Beta normal form]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fixed-point_combinator