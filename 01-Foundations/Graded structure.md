---
title: "Graded structure"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graded_structure"
wikipedia_categories: ["Differential operators", "Linear algebra", "Set index articles on mathematics"]
related: ["[[Homogeneous function]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]"]
---

# Graded structure

In mathematics, the term "graded" has a number of meanings, mostly related:
In abstract algebra, it refers to a family of concepts:

An algebraic structure 
  
    
      
        X
      
    
    
  
 is said to be 
  
    
      
        I
      
    
    
  
-graded for an index set 
  
    
      
        I
      
    
    
  
 if it has a gradation or grading, i.e. a decomposition into a direct sum 
  
    
      
        X
        
          ⨁
          
            i
            ∈
            I
          
        
        
          X
          
            i
          
        
      
    
    {\textstyle X=\bigoplus _{i\in I}X_{i}}
  
 of structures; the elements of 
  
    
      
        
          X
          
            i
          
        
      
    
    
  
 are said to be "homogeneous of degree i".
The index set 
  
    
      
        I
      
    
    
  
 is most commonly 
  
    
      
        
          N
        
      
    
    
  
 or 
  
    
      
        
          Z
        
      
    
    
  
, and may be required to have extra structure depending on the type of 
  
    
      
        X
      
    
    
  
.
Grading by 
  
    
      
        
          
            Z
          
          
            2
          
        
      
    
    
  
 (i.e. 
  
    
      
        
          Z
        
        
          /
        
        2
        
          Z
        
      
    
    
  
) is also important; see e.g. signed set (the 
  
    
      
        
          
            Z
          
          
            2
          
        
      
    
    
  
-graded sets).
The trivial (
  
    
      
        
          Z
        
      
    
    
  
- or 
  
    
      
        
          N
        
      
    
    
  
-) gradation has 
  
    
      
        
          X
          
            0
          
        
        X
        ,
        
          X
          
            i
          
        
        0
      
    
    
  
 for 
  
    
      
        i
        ≠
        0
      
    
    
  
 and a suitable trivial structure 
  
    
      
        0
      
    
    
  
.
An algebraic structure is said to be doubly graded if the index set is a direct product of sets; the pairs may be called "bidegrees" (e.g. see Spectral sequence).
A 
  
    
      
        I
      
    
    
  
-graded vector space or graded linear space is thus a vector space with a decomposition into a direct sum 
  
    
      
        V
        
          ⨁
          
            i
            ∈
            I
          
        
        
          V
          
            i
          
        
      
    
    {\textstyle V=\bigoplus _{i\in I}V_{i}}
  
 of spaces.
A graded linear map is a map between graded vector spaces respecting their gradations.
A graded ring is a ring that is a direct sum of additive abelian groups 
  
    
      
        
          R
          
            i
          
        
      
    
    
  
 such that 
  
    
      
        
          R
          
            i
          
        
        
          R
          
            j
          
        
        ⊆
        
          R
          
            i
            j
          
        
      
    
    
  
, with 
  
    
      
        i
      
    
    
  
 taken from some monoid, usually 
  
    
      
        
          N
        
      
    
    
  
 or 
  
    
      
        
          Z
        
      
    
    
  
, or semigroup (for a ring without identity).
The associated graded ring of a commutative ring 
  
    
      
        R
      
    
    
  
 with respect to a proper ideal 
  
    
      
        I
      
    
    
  
 is 
  
    
      
        
          gr
          
            I
          
        
         
        R
        
          ⨁
          
            n
            ∈
            
              N
            
          
        
        
          I
          
            n
          
        
        
          /
        
        
          I
          
            n
            1
          
        
      
    
    {\textstyle \operatorname {gr} _{I}R=\bigoplus _{n\in \mathbb {N} }I^{n}/I^{n+1}}
  
.
A graded module is left module 
  
    
      
        M
      
    
    
  
 over a graded ring that is a direct sum 
  
    
      
        
          ⨁
          
            i
            ∈
            I
          
        
        
          M
          
            i
          
        
      
    
    {\textstyle \bigoplus _{i\in I}M_{i}}
  
 of modules satisfying 
  
    
      
        
          R
          
            i
          
        
        
          M
          
            j
          
        
        ⊆
        
          M
          
            i
            j
          
        
      
    
    
  
.
The associated graded module of an 
  
    
      
        R
      
    
    
  
-module 
  
    
      
        M
      
    
    
  
 with respect to a proper ideal 
  
    
      
        I
      
    
    
  
 is 
  
    
      
        
          gr
          
            I
          
        
         
        M
        
          ⨁
          
            n
            ∈
            
              N
            
          
        
        
          I
          
            n
          
        
        M
        
          /
        
        
          I
          
            n
            1
          
        
        M
      
    
    {\textstyle \operatorname {gr} _{I}M=\bigoplus _{n\in \mathbb {N} }I^{n}M/I^{n+1}M}
  
.
A differential graded module, differential graded 
  
    
      
        
          Z
        
      
    
    
  
-module or DG-module is a graded module 
  
    
      
        M
      
    
    
  
 with a differential 
  
    
      
        d
        :
        M
        →
        M
        :
        
          M
          
            i
          
        
        →
        
          M
          
            i
            1
          
        
      
    
    
  
 making 
  
    
      
        M
      
    
    
  
 a chain complex, i.e. 
  
    
      
        d
        ∘
        d
        0
      
    
    
  
 .
A graded algebra is an algebra 
  
    
      
        A
      
    
    
  
 over a ring 
  
    
      
        R
      
    
    
  
 that is graded as a ring; if 
  
    
      
        R
      
    
    
  
 is graded we also require 
  
    
      
        
          A
          
            i
          
        
        
          R
          
            j
          
        
        ⊆
        
          A
          
            i
            j
          
        
        ⊇
        
          R
          
            i
          
        
        
          A
          
            j
          
        
      
    
    
  
.
The graded Leibniz rule for a map 
  
    
      
        d
        :
        A
        →
        A
      
    
    
  
 on a graded algebra 
  
    
      
        A
      
    
    
  
 specifies that 
  
    
      
        d
        a
        ⋅
        b
        =
        d
        a
        ⋅
        b
        (
        1
        
          
            
              |
            
            a
            
              |
            
          
        
        a
        ⋅
        d
        b
      
    
    
  
.
A differential graded algebra, DG-algebra or DGAlgebra is a graded algebra that is a differential graded module whose differential obeys the graded Leibniz rule.
A homogeneous derivation on a graded algebra A is a homogeneous linear map of grade d = |D| on A such that 
  
    
      
        D
        a
        b
        =
        D
        a
        b
        
          ε
          
            
              |
            
            a
            
              |
            
            
              |
            
            D
            
              |
            
          
        
        a
        D
        b
        ,
        ε
        ±
        1
      
    
    
  
 acting on homogeneous elements of A.
A graded derivation  is a sum of homogeneous derivations with the same 
  
    
      
        ε
      
    
    
  
.
A DGA is an augmented DG-algebra, or differential graded augmented algebra, (see Differential graded algebra).
A superalgebra is a 
  
    
      
        
          
            Z
          
          
            2
          
        
      
    
    
  
-graded algebra.
A graded-commutative superalgebra satisfies the "supercommutative" law 
  
    
      
        y
        x
        (
        1
        
          
            
              |
            
            x
            
              |
            
            
              |
            
            y
            
              |
            
          
        
        x
        y
        .
      
    
    
  
 for homogeneous x,y, where 
  
    
      
        
          |
        
        a
        
          |
        
      
    
    
  
 represents the "parity" of 
  
    
      
        a
      
    
    
  
, i.e. 0 or 1 depending on the component in which it lies.
CDGA may refer to the category of augmented differential graded commutative algebras.
A graded Lie algebra is a Lie algebra that is graded as a vector space by a gradation compatible with its Lie bracket.
A graded Lie superalgebra is a graded Lie algebra with the requirement for anticommutativity of its Lie bracket relaxed.
A supergraded Lie superalgebra is a graded Lie superalgebra with an additional super 
  
    
      
        
          
            Z
          
          
            2
          
        
      
    
    
  
-gradation.
A differential graded Lie algebra is a graded vector space over a field of characteristic zero together with a bilinear map 
  
    
      
         
        ,
        :
        
          L
          
            i
          
        
        ⊗
        
          L
          
            j
          
        
        →
        
          L
          
            i
            j
          
        
      
    
    
  
 and a differential 
  
    
      
        d
        :
        
          L
          
            i
          
        
        →
        
          L
          
            i
            1
          
        
      
    
    
  
 satisfying 
  
    
      
        x
        ,
        y
        =
        −
        1
        
          
            
              |
            
            x
            
              |
            
            
              |
            
            y
            
              |
            
            1
          
        
        y
        ,
        x
        ,
      
    
    
  
 for any homogeneous elements x, y in L, the "graded Jacobi identity" and the graded Leibniz rule.
The Graded Brauer group is a synonym for the Brauer–Wall group 
  
    
      
        B
        W
        F
      
    
    
  
 classifying finite-dimensional graded central division algebras over the field F.
An 
  
    
      
        
          
            A
          
        
      
    
    
  
-graded category for a category 
  
    
      
        
          
            A
          
        
      
    
    
  
 is a category 
  
    
      
        
          
            C
          
        
      
    
    
  
 together with a functor 
  
    
      
        F
        :
        
          
            C
          
        
        →
        
          
            A
          
        
      
    
    
  
.
A differential graded category or  DG category is a category whose morphism sets form differential graded 
  
    
      
        
          Z
        
      
    
    
  
-modules.
Graded manifold – extension of the manifold concept based on ideas coming from supersymmetry and supercommutative algebra, including sections on
Graded function
Graded vector fields
Graded exterior forms
Graded differential geometry
Graded differential calculus
In other areas of mathematics:

Functionally graded elements are used in finite element analysis.
A graded poset is a poset 
  
    
      
        P
      
    
    
  
 with a rank function 
  
    
      
        ρ
        :
        P
        →
        
          N
        
      
    
    
  
 compatible with the ordering (i.e. 
  
    
      
        ρ
        x
        <
        ρ
        y
        
        ⟹
        
        x
        y
      
    
    
  
) such that 
  
    
      
        y
      
    
    
  
 covers 
  
    
      
        x
        
        ⟹
        
        ρ
        y
        =
        ρ
        x
        +
        1
      
    
    
  
 .

*(note truncated for size; full article at the source link below)*

## Related

- [[Homogeneous function]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graded_structure