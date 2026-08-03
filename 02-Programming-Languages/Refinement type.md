---
title: "Refinement type"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Refinement_type"
wikipedia_categories: ["Programming language theory stubs", "Type systems", "Type theory"]
related: ["[[Container (type theory)]]", "[[Dependent type]]", "[[Flow-sensitive typing]]", "[[Hindley–Milner type system]]", "[[Intersection type]]", "[[Intersection type discipline]]", "[[Principal type]]", "[[Session type]]", "[[Stream (abstract data type)]]", "[[Type inference]]"]
---

# Refinement type

In type theory, a refinement type is a type endowed with a predicate which is assumed to hold for any element of the refined type.  Refinement types can express preconditions when used as function arguments or postconditions when used as return types:  for instance, the type of a function which accepts natural numbers and returns natural numbers greater than 5 may be written as 
  
    
      
        f
        :
        
          N
        
        →
        n
        ∈
        
          N
        
        
        
          |
        
        
        n
        5
      
    
    
  
.  Refinement types are thus related to behavioral subtyping.

## Related

- [[Container (type theory)]]
- [[Dependent type]]
- [[Flow-sensitive typing]]
- [[Hindley–Milner type system]]
- [[Intersection type]]
- [[Intersection type discipline]]
- [[Principal type]]
- [[Session type]]
- [[Stream (abstract data type)]]
- [[Type inference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Refinement_type