---
title: "Monad (category theory)"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Monad_(category_theory)"
wikipedia_categories: ["Adjoint functors", "Category theory"]
related: ["[[Beck's monadicity theorem]]", "[[Cotriple homology]]", "[[Equivalence of categories]]", "[[Isbell duality]]", "[[Kan extension]]", "[[Pseudoalgebra]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[AB5 category]]", "[[Abstract elementary class]]"]
---

# Monad (category theory)

In category theory, a branch of mathematics, a monad is a triple 
  
    
      
        T
        ,
        η
        ,
        μ
      
    
    
  
 consisting of a functor T from a category to itself and two natural transformations 
  
    
      
        η
        ,
        μ
      
    
    
  
 that satisfy versions of the associativity and unitality axioms.  
Equivalently, a monad is a monoid in the category of endofunctors of some fixed category (an endofunctor is a functor mapping a category to itself).
For example, if 
  
    
      
        F
        ,
        G
      
    
    
  
 are functors adjoint to each other, then 
  
    
      
        T
        G
        ∘
        F
      
    
    
  
 together with 
  
    
      
        η
        ,
        μ
      
    
    
  
 determined by the adjoint relation is a monad.
According to mathematician John Baez, a monad can be considered at least in two ways:

A monad as a generalized monoid; this is clear since a monad is a monoid in a certain category,
A monad as a tool for studying algebraic gadgets; for example, a group can be described by a certain monad.
Monads are used in the theory of pairs of adjoint functors, and they generalize closure operators on partially ordered sets to arbitrary categories. Monads are also useful in the theory of datatypes, the denotational semantics of imperative programming languages, and in functional programming languages, allowing languages without mutable state to do things such as simulate for-loops; see Monad (functional programming).
A monad is also called, especially in old literature, a triple, triad, standard construction and fundamental construction.

## Related

- [[Beck's monadicity theorem]]
- [[Cotriple homology]]
- [[Equivalence of categories]]
- [[Isbell duality]]
- [[Kan extension]]
- [[Pseudoalgebra]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[AB5 category]]
- [[Abstract elementary class]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Monad_(category_theory)