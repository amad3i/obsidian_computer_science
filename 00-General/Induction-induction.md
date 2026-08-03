---
title: "Induction-induction"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Induction-induction"
wikipedia_categories: ["Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# Induction-induction

In intuitionistic type theory (ITT), a discipline within mathematical logic, induction-induction is for simultaneously declaring some inductive type and some inductive predicate over this type.
An inductive definition is given by rules for generating elements of some type. One can then define some predicate on that type by providing constructors for forming the elements of the predicate, such inductively on the way the elements of the type are generated. Induction-induction generalizes this situation since one can simultaneously define the type and the predicate, because the rules for generating elements of the type 
  
    
      
        A
        :
        
          
            T
            y
            p
            e
          
        
      
    
    
  
 are allowed to refer to the predicate 
  
    
      
        B
        :
        A
        →
        
          
            T
            y
            p
            e
          
        
      
    
    
  
.
Induction-induction can be used to define larger types including various universe constructions in type theory. and limit constructions in category/topos theory.

## Related

- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Attribute domain]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bottom type]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Induction-induction