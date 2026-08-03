---
title: "Intersection type discipline"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Intersection_type_discipline"
wikipedia_categories: ["Lambda calculus", "Polymorphism (computer science)", "Theory of computation", "Type systems", "Type theory"]
related: ["[[Hindley–Milner type system]]", "[[Intersection type]]", "[[Simply typed lambda calculus]]", "[[System F]]", "[[Typed lambda calculus]]", "[[Ad hoc polymorphism]]", "[[Bounded quantification]]", "[[Calculus of constructions]]", "[[Dependent type]]", "[[Flow-sensitive typing]]"]
---

# Intersection type discipline

In mathematical logic, the intersection type discipline is a branch of type theory encompassing type systems that use the intersection type constructor 
  
    
      
        ∩
      
    
    
  
 to assign multiple types to a single term.
In particular, if a term 
  
    
      
        M
      
    
    
  
 can be assigned both the type 
  
    
      
        
          φ
          
            1
          
        
      
    
    
  
 and the type 
  
    
      
        
          φ
          
            2
          
        
      
    
    
  
, then 
  
    
      
        M
      
    
    
  
 can be assigned the intersection type 
  
    
      
        
          φ
          
            1
          
        
        ∩
        
          φ
          
            2
          
        
      
    
    
  
 (and vice versa).
Therefore, the intersection type constructor can be used to express finite heterogeneous ad hoc polymorphism (as opposed to parametric polymorphism).
For example, the λ-term 
  
    
      
        λ
        x
        .
        
        x
        
        x
      
    
    
  
 can be assigned the type 
  
    
      
        (
        α
        →
        β
        ∩
        α
        →
        β
      
    
    
  
 in most intersection type systems, assuming for the term variable 
  
    
      
        x
      
    
    
  
 both the function type 
  
    
      
        α
        →
        β
      
    
    
  
 and the corresponding argument type 
  
    
      
        α
      
    
    
  
.
Prominent intersection type systems include the Coppo–Dezani type assignment system, the Barendregt-Coppo–Dezani type assignment system, and the essential intersection type assignment system.
Most strikingly, intersection type systems are closely related to (and often exactly characterize) normalization properties of λ-terms under β-reduction.
In programming languages, such as TypeScript and Scala, intersection types are used to express ad hoc polymorphism.

## Related

- [[Hindley–Milner type system]]
- [[Intersection type]]
- [[Simply typed lambda calculus]]
- [[System F]]
- [[Typed lambda calculus]]
- [[Ad hoc polymorphism]]
- [[Bounded quantification]]
- [[Calculus of constructions]]
- [[Dependent type]]
- [[Flow-sensitive typing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Intersection_type_discipline