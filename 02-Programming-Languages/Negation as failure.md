---
title: "Negation as failure"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Negation_as_failure"
wikipedia_categories: ["Logic programming", "Rules of inference"]
related: ["[[SLD resolution]]", "[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Circumscription (logic)]]", "[[Clause (logic)]]"]
---

# Negation as failure

Negation as failure (NAF, for short) is a non-monotonic inference rule in logic programming, used to derive 
  
    
      
        
          n
          o
          t
        
         
        p
      
    
    
  
 (i.e. that 
  
    
      
        p
      
    
    
  
 is assumed not to hold) from failure to derive 
  
    
      
        p
      
    
    
  
.  Note that 
  
    
      
        
          n
          o
          t
        
         
        p
      
    
    
  
 can be different from the statement 
  
    
      
        ¬
        p
      
    
    
  
 of the logical negation of 
  
    
      
        p
      
    
    
  
, depending on the completeness of the inference algorithm and thus also on the formal logic system.
Negation as failure has been an important feature of logic programming since the earliest days of both Planner and Prolog. In Prolog, it is usually implemented using Prolog's extralogical constructs.
More generally, this kind of negation is known as weak negation, in contrast with the strong (i.e. explicit, provable) negation.

## Related

- [[SLD resolution]]
- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Circumscription (logic)]]
- [[Clause (logic)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Negation_as_failure