---
title: "Liskov substitution principle"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Liskov_substitution_principle"
wikipedia_categories: ["Formal methods", "Object-oriented programming", "Programming language semantics", "Programming principles", "Type theory"]
related: ["[[Open–closed principle]]", "[[Algebraic semantics (computer science)]]", "[[Bounded quantification]]", "[[Command–query separation]]", "[[Coupling (computer programming)]]", "[[Duck typing]]", "[[Encapsulation (computer programming)]]", "[[Hindley–Milner type system]]", "[[Homotopy type theory]]", "[[Information hiding]]"]
---

# Liskov substitution principle

The Liskov substitution principle (LSP) is a particular definition of a subtyping relation, called strong behavioral subtyping, that was initially introduced by Barbara Liskov in a 1987 conference keynote address titled Data abstraction and hierarchy. It is based on the concept of "substitutability" – a principle in object-oriented programming stating that an object of a superclass may be replaced by an object of a subclass without breaking the program. It is a semantic rather than merely syntactic relation, because it intends to guarantee semantic interoperability of types in a hierarchy, object types in particular. Barbara Liskov and Jeannette Wing described the principle succinctly in a 1994 paper as follows:

Subtype Requirement: Let ⁠
  
    
      
        ϕ
        x
      
    
    
  
⁠ be a property provable about objects ⁠
  
    
      
        x
      
    
    
  
⁠ of type T. Then ⁠
  
    
      
        ϕ
        y
      
    
    
  
⁠ should be true for objects ⁠
  
    
      
        y
      
    
    
  
⁠ of type S where S is a subtype of T. 
Symbolically:

  
    
      
        
          
            S
          
        
        ≤
        
          
            T
          
        
        →
        ∀
        x
        
          :
        
        
          
            T
          
        
        .
        ϕ
        x
        →
        ∀
        y
        
          :
        
        
          
            S
          
        
        .
        ϕ
        y
        )
      
    
    
  

That is, if S subtypes T, what holds for T-objects holds for S-objects.
In the same paper, Liskov and Wing detailed their notion of behavioral subtyping in an extension of Hoare logic, which bears a certain resemblance to Bertrand Meyer's design by contract in that it considers the interaction of subtyping with preconditions, postconditions and invariants.

## Related

- [[Open–closed principle]]
- [[Algebraic semantics (computer science)]]
- [[Bounded quantification]]
- [[Command–query separation]]
- [[Coupling (computer programming)]]
- [[Duck typing]]
- [[Encapsulation (computer programming)]]
- [[Hindley–Milner type system]]
- [[Homotopy type theory]]
- [[Information hiding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Liskov_substitution_principle