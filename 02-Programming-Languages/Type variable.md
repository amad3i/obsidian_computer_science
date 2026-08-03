---
title: "Type variable"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Type_variable"
wikipedia_categories: ["Dependently typed programming", "Functional programming", "Generic programming", "Programming language comparisons", "Type theory"]
related: ["[[Polymorphism (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Generalized algebraic data type]]", "[[Option type]]", "[[Type class]]", "[[Algebraic data type]]", "[[Calculus of constructions]]", "[[Curry–Howard correspondence]]", "[[Dependent type]]", "[[Flow-sensitive typing]]"]
---

# Type variable

In type theory and programming languages, a type variable is a mathematical variable ranging over types. Even in programming languages that allow mutable variables, a type variable remains an abstraction, in the sense that it does not correspond to some memory locations.
Programming languages that support parametric polymorphism make use of universally quantified type variables. Languages that support existential types make use of existentially quantified type variables. For example, the following OCaml code defines a polymorphic identity function that has a universally quantified type, which is printed by the interpreter on the second line:

In mathematical notation, the type of the function id is 
  
    
      
        ∀
        a
        .
        a
        →
        a
      
    
    
  
, where 
  
    
      
        a
      
    
    
  
 is a type variable.

## Related

- [[Polymorphism (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Generalized algebraic data type]]
- [[Option type]]
- [[Type class]]
- [[Algebraic data type]]
- [[Calculus of constructions]]
- [[Curry–Howard correspondence]]
- [[Dependent type]]
- [[Flow-sensitive typing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Type_variable