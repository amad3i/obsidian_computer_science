---
title: "Dependent type"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Dependent_type"
wikipedia_categories: ["Dependently typed programming", "Foundations of mathematics", "Type systems", "Type theory"]
related: ["[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Intuitionistic type theory]]", "[[Axiom of reducibility]]", "[[Calculus of constructions]]", "[[Curry–Howard correspondence]]", "[[Flow-sensitive typing]]", "[[Generalized algebraic data type]]", "[[Higher-order abstract syntax]]", "[[Hindley–Milner type system]]", "[[Homotopy type theory]]"]
---

# Dependent type

In computer science and logic, a dependent type is a type whose definition depends on a value. It is an overlapping feature of type theory and type systems. In intuitionistic type theory, dependent types are used to encode logic's quantifiers like "for all" and "there exists". In functional programming languages like Agda, ATS, Rocq (previously known as Coq), F*, Epigram, Idris, and Lean, dependent types help reduce bugs by enabling the programmer to assign types that further restrain the set of possible implementations.
Two common examples of dependent types are dependent functions and dependent pairs. The return type of a dependent function may depend on the value (not just type) of one of its arguments. For instance, a function that takes a positive integer 
  
    
      
        n
      
    
    
  
 may return an array of length 
  
    
      
        n
      
    
    
  
, where the array length is part of the type of the array. (Note that this is different from polymorphism and generic programming, both of which include the type as an argument.) A dependent pair may have a second value, the type of which depends on the first value. Sticking with the array example, a dependent pair may be used to pair an array with its length in a type-safe way.
Dependent types add complexity to a type system. Deciding the equality of dependent types in a program may require computations. If arbitrary values are allowed in dependent types, then deciding type equality may involve deciding whether two arbitrary programs produce the same result; hence the decidability of type checking may depend on the given type theory's semantics of equality, that is, whether the type theory is intensional or extensional.

## Related

- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Intuitionistic type theory]]
- [[Axiom of reducibility]]
- [[Calculus of constructions]]
- [[Curry–Howard correspondence]]
- [[Flow-sensitive typing]]
- [[Generalized algebraic data type]]
- [[Higher-order abstract syntax]]
- [[Hindley–Milner type system]]
- [[Homotopy type theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dependent_type