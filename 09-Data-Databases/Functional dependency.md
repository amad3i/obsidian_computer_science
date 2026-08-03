---
title: "Functional dependency"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Functional_dependency"
wikipedia_categories: ["Data modeling"]
related: ["[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]", "[[Building information modeling]]", "[[BuildingSMART Data Dictionary]]", "[[Business rule management system]]", "[[Cadwork Engineer]]", "[[Candidate key]]"]
---

# Functional dependency

In relational database theory, a functional dependency (FD) is constraint between two attribute sets, whereby values in one set (the determinant set) determine the values of the other set (the dependent set). A functional dependency between a determinant set X and a dependent set Y can be described as follows:
Given a relation R and attribute sets X,Y 
  
    
      
        ⊆
      
    
    
  
 R, then X is said to functionally determine Y (written X → Y) if each X value is associated with precisely one Y value. R is then said to satisfy the functional dependency X → Y. Equivalently, the projection 
  
    
      
        
          Π
          
            X
            ,
            Y
          
        
        R
      
    
    
  
 is a function, that is, Y is a function of X. 
In other words:

when X attributes have known values (here, x), the values for their corresponding Y attributes can be determined by looking them up in any tuple of R containing x.
two tuples sharing the same values of X will necessarily have the same values of Y.
A dependency FD: X → Y means that the values of Y are determined by the values of X. A functional dependency FD: X → Y is called trivial if Y is a subset of X.
The determination of functional dependencies is an important part of designing databases in the relational model, and in database normalization and denormalization. A simple application of functional dependencies is Heath's theorem; it says that a relation R over an attribute set U and satisfying a functional dependency X → Y can be safely split in two relations having the lossless-join decomposition property, namely into 
  
    
      
        
          Π
          
            X
            Y
          
        
        R
        ⋈
        
          Π
          
            X
            Z
          
        
        R
        =
        R
      
    
    
  
 where Z = U − XY are the rest of the attributes. (Unions of attribute sets are customarily denoted by their juxtapositions in database theory.) An important notion in this context is a candidate key, defined as a minimal set of attributes that functionally determine all of the attributes in a relation. The functional dependencies, along with the attribute domains, are selected so as to generate constraints that would exclude as much data inappropriate to the user domain from the system as possible.
A notion of logical implication is defined for functional dependencies in the following way: a set of functional dependencies 
  
    
      
        Σ
      
    
    
  
 logically implies another set of dependencies 
  
    
      
        Γ
      
    
    
  
, if any relation R satisfying all dependencies from  
  
    
      
        Σ
      
    
    
  
 also satisfies all dependencies from 
  
    
      
        Γ
      
    
    
  
; this is usually written 
  
    
      
        Σ
        ⊨
        Γ
      
    
    
  
. The notion of logical implication for functional dependencies admits a sound and complete finite axiomatization, known as Armstrong's axioms.

## Related

- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Bitemporal modeling]]
- [[Building information modeling]]
- [[BuildingSMART Data Dictionary]]
- [[Business rule management system]]
- [[Cadwork Engineer]]
- [[Candidate key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Functional_dependency