---
title: "Partial application"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Partial_application"
wikipedia_categories: ["Functional programming", "Implementation of functional programming languages"]
related: ["[[A-normal form]]", "[[Continuation-passing style]]", "[[Supercombinator]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Catamorphism]]"]
---

# Partial application

In computer science, partial application (or partial function application) refers to the process of fixing a number of arguments of a function, producing another function of smaller arity.  Given a function 
  
    
      
        f
        :
        X
        Y
        Z
        →
        N
      
    
    
  
, we might fix (or 'bind') the first argument, producing a function of type 
  
    
      
        
          partial
        
        f
        :
        Y
        Z
        →
        N
      
    
    
  
.  Evaluation of this function might be represented as 
  
    
      
        
          f
          
            partial
          
        
        2
        ,
        3
      
    
    
  
.  Note that the result of partial function application in this case is a function that takes two arguments. Partial application is sometimes incorrectly called currying, which is a related, but distinct concept.

## Related

- [[A-normal form]]
- [[Continuation-passing style]]
- [[Supercombinator]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Catamorphism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partial_application