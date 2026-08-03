---
title: "System F"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/System_F"
wikipedia_categories: ["1971 in computing", "1974 in computing", "Lambda calculus", "Logic", "Polymorphism (computer science)", "Type theory"]
related: ["[[Intersection type discipline]]", "[[Ad hoc polymorphism]]", "[[Bounded quantification]]", "[[Calculus of constructions]]", "[[Hindley–Milner type system]]", "[[Intersection type]]", "[[Lambda cube]]", "[[Parametric polymorphism]]", "[[Parametricity]]", "[[Polymorphism (computer science)]]"]
---

# System F

System F (also polymorphic lambda calculus or second-order lambda calculus) is a typed lambda calculus that introduces, to simply typed lambda calculus, a mechanism of universal quantification over types. System F formalizes parametric polymorphism in programming languages, thus forming a theoretical basis for languages such as Haskell and ML. It was discovered independently by logician Jean-Yves Girard (1972) and computer scientist John C. Reynolds.
Whereas simply typed lambda calculus has variables ranging over terms, and binders for them, System F additionally has variables ranging over types, and binders for them. As an example, the fact that the identity function can have any type of the form A → A would be formalized in System F as the statement

  
    
      
        ⊢
        Λ
        α
        .
        λ
        
          x
          
            α
          
        
        .
        x
        :
        ∀
        α
        .
        α
        →
        α
      
    
    
  

where 
  
    
      
        α
      
    
    
  
 is a type variable. The upper-case 
  
    
      
        Λ
      
    
    
  
 is traditionally used to denote type-level functions, as opposed to the lower-case 
  
    
      
        λ
      
    
    
  
 which is used for value-level functions. (The superscripted 
  
    
      
        α
      
    
    
  
 means that the bound variable x is of type 
  
    
      
        α
      
    
    
  
; the expression after the colon is the type of the lambda expression preceding it.)
As a term rewriting system, System F is strongly normalizing. However, type inference in System F (without explicit type annotations) is undecidable. Under the Curry–Howard isomorphism, System F corresponds to second-order propositional intuitionistic logic. System F can be seen as part of the lambda cube, together with even more expressive typed lambda calculi, including those with dependent types.
According to Girard, the "F" in System F was picked by chance.

## Related

- [[Intersection type discipline]]
- [[Ad hoc polymorphism]]
- [[Bounded quantification]]
- [[Calculus of constructions]]
- [[Hindley–Milner type system]]
- [[Intersection type]]
- [[Lambda cube]]
- [[Parametric polymorphism]]
- [[Parametricity]]
- [[Polymorphism (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/System_F