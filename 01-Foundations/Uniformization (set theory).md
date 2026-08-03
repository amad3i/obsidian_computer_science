---
title: "Uniformization (set theory)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Uniformization_(set_theory)"
wikipedia_categories: ["Axiom of choice", "Descriptive set theory", "Set theory"]
related: ["[[Cabal (set theory)]]", "[[Diaconescu's theorem]]", "[[Tarski's theorem about choice]]", "[[Admissible set]]", "[[Almost]]", "[[Basis (linear algebra)]]", "[[Benacerraf's identification problem]]", "[[BIT predicate]]", "[[Cantor's diagonal argument]]", "[[Cantor's first set theory article]]"]
---

# Uniformization (set theory)

In set theory, a branch of mathematics, the axiom of uniformization is a weak form of the axiom of choice. It states that if 
  
    
      
        R
      
    
    
  
 is a subset of 
  
    
      
        X
        Y
      
    
    
  
, where 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 are Polish spaces, then there is a subset 
  
    
      
        f
      
    
    
  
 of 
  
    
      
        R
      
    
    
  
 that is a partial function from 
  
    
      
        X
      
    
    
  
 to 
  
    
      
        Y
      
    
    
  
, and whose domain (the set of all 
  
    
      
        x
      
    
    
  
 such that 
  
    
      
        f
        x
      
    
    
  
 exists) equals

  
    
      
        x
        ∈
        X
        ∣
        ∃
        y
        ∈
        Y
        :
        x
        ,
        y
        ∈
        R
        
      
    
    
  

Such a function is called a uniformizing function for 
  
    
      
        R
      
    
    
  
, or a uniformization of 
  
    
      
        R
      
    
    
  
.

To see the relationship with the axiom of choice, observe that 
  
    
      
        R
      
    
    
  
 can be thought of as associating, to each element of 
  
    
      
        X
      
    
    
  
, a subset of 
  
    
      
        Y
      
    
    
  
.  A uniformization of 
  
    
      
        R
      
    
    
  
 then picks exactly one element from each such subset, whenever the subset is non-empty.  Thus, allowing arbitrary sets X and Y (rather than just Polish spaces) would make the axiom of uniformization equivalent to the axiom of choice. 
A pointclass 
  
    
      
        
          Γ
        
      
    
    
  
 is said to have the uniformization property if every relation 
  
    
      
        R
      
    
    
  
 in 
  
    
      
        
          Γ
        
      
    
    
  
 can be uniformized by a partial function in 
  
    
      
        
          Γ
        
      
    
    
  
.  The uniformization property is implied by the scale property, at least for adequate pointclasses of a certain form.
It follows from ZFC alone that 
  
    
      
        
          
            Π
          
          
            1
          
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          
            Σ
          
          
            2
          
          
            1
          
        
      
    
    
  
 have the uniformization property. It follows from the existence of sufficient large cardinals that

  
    
      
        
          
            Π
          
          
            2
            n
            1
          
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          
            Σ
          
          
            2
            n
            2
          
          
            1
          
        
      
    
    
  
 have the uniformization property for every natural number 
  
    
      
        n
      
    
    
  
.
Therefore, the collection of projective sets has the uniformization property.
Every relation in L(R) can be uniformized, but not necessarily by a function in L(R). In fact, L(R) does not have the uniformization property (equivalently, L(R) does not satisfy the axiom of uniformization).
(Note: it's trivial that every relation in L(R) can be uniformized in V, assuming V satisfies the axiom of choice. The point is that every such relation can be uniformized in some transitive inner model of V in which the axiom of determinacy holds.)

## Related

- [[Cabal (set theory)]]
- [[Diaconescu's theorem]]
- [[Tarski's theorem about choice]]
- [[Admissible set]]
- [[Almost]]
- [[Basis (linear algebra)]]
- [[Benacerraf's identification problem]]
- [[BIT predicate]]
- [[Cantor's diagonal argument]]
- [[Cantor's first set theory article]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Uniformization_(set_theory)