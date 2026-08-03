---
title: "Empty type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Empty_type"
wikipedia_categories: ["Theoretical computer science stubs", "Type theory", "Unknown content"]
related: ["[[Void type]]", "[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]"]
---

# Empty type

In type theory, an empty type or absurd type, typically denoted 
  
    
      
        
          0
        
      
    
    
  
 is a type with no terms. Such a type may be defined as the nullary coproduct (i.e. disjoint sum of no types). It may also be defined as the polymorphic type 
  
    
      
        ∀
        t
        .
        t
      
    
    
  

For any type 
  
    
      
        P
      
    
    
  
, the type 
  
    
      
        ¬
        P
      
    
    
  
 is defined as 
  
    
      
        P
        →
        
          0
        
      
    
    
  
. As the notation suggests, by the Curry–Howard correspondence, a term of type 
  
    
      
        
          0
        
      
    
    
  
 is a false proposition, and a term of type 
  
    
      
        ¬
        P
      
    
    
  
 is a disproof of proposition P.
A type theory need not contain an empty type. Where it exists, an empty type is not generally unique. For instance, 
  
    
      
        T
        →
        
          0
        
      
    
    
  
 is also uninhabited for any inhabited type 
  
    
      
        T
      
    
    
  
.
If a type system contains an empty type, the bottom type must be uninhabited too, so no distinction is drawn between them and both are denoted 
  
    
      
        ⊥
      
    
    
  
.

## Related

- [[Void type]]
- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Attribute domain]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bottom type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Empty_type