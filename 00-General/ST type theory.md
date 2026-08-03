---
title: "ST type theory"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/ST_type_theory"
wikipedia_categories: ["Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# ST type theory

The following system is Mendelson's (1997, 289–293) ST type theory. 
ST is equivalent with Russell's ramified theory plus the Axiom of reducibility. 
The domain of quantification is partitioned into an ascending hierarchy of types, with all individuals assigned a type. Quantified variables range over only one type; hence the underlying logic is first-order logic. ST is "simple" (relative to the type theory of Principia Mathematica) primarily because all members of the domain and codomain of any relation must be of the same type.
There is a lowest type, whose individuals have no members and are members of the second lowest type. Individuals of the lowest type correspond to the urelements of certain set theories. Each type has a next higher type, analogous to the notion of successor in Peano arithmetic. While ST is silent as to whether there is a maximal type, a transfinite number of types poses no difficulty. These facts, reminiscent of the Peano axioms, make it convenient and conventional to assign a natural number to each type, starting with 0 for the lowest type. But type theory does not require a prior definition of the naturals.
The symbols peculiar to ST are primed variables and infix operator 
  
    
      
        ∈
      
    
    
  
. In any given formula, unprimed variables all have the same type, while primed variables (
  
    
      
        
          x
          ′
        
      
    
    
  
) range over the next higher type. The atomic formulas of ST are of two forms, 
  
    
      
        x
        y
      
    
    
  
 (identity) and 
  
    
      
        y
        ∈
        
          x
          ′
        
      
    
    
  
. The infix-operator symbol 
  
    
      
        ∈
      
    
    
  
 suggests the intended interpretation, set membership.
All variables appearing in the definition of identity and in the axioms Extensionality and Comprehension, range over individuals of one of two consecutive types. Only unprimed variables (ranging over the "lower" type) can appear to the left of '
  
    
      
        ∈
      
    
    
  
', whereas to its right, only primed variables (ranging over the "higher" type) can appear. The first-order formulation of ST rules out quantifying over types. Hence each pair of consecutive types requires its own axiom of Extensionality and of Comprehension, which is possible if Extensionality and Comprehension below are taken as axiom schemata "ranging over" types.

Identity, defined by 
  
    
      
        x
        y
        ↔
        ∀
        
          z
          ′
        
        x
        ∈
        
          z
          ′
        
        ↔
        y
        ∈
        
          z
          ′
        
      
    
    
  
.
Extensionality.  An axiom schema. 
  
    
      
        ∀
        x
        x
        ∈
        
          y
          ′
        
        ↔
        x
        ∈
        
          z
          ′
        
        →
        
          y
          ′
        
        
          z
          ′
        
      
    
    
  
.
Let 
  
    
      
        Φ
        x
      
    
    
  
 denote any first-order formula containing the free variable 
  
    
      
        x
      
    
    
  
.

Comprehension.  An axiom schema. 
  
    
      
        ∃
        
          z
          ′
        
        ∀
        x
        x
        ∈
        
          z
          ′
        
        ↔
        Φ
        x
        ]
      
    
    
  
.
Remark. Any collection of elements of the same type may form an object of the next higher type. Comprehension is schematic with respect to 
  
    
      
        Φ
        x
      
    
    
  
 as well as to types.
Infinity.  There exists a nonempty binary relation 
  
    
      
        R
      
    
    
  
 over the individuals of the lowest type, that is irreflexive, transitive, and strongly connected: 
  
    
      
        ∀
        x
        ,
        y
        x
        ≠
        y
        →
        x
        R
        y
        ∨
        y
        R
        x
        ]
      
    
    
  
 and with codomain contained in domain.
Remark. Infinity is the only true axiom of ST and is entirely mathematical in nature. It asserts that 
  
    
      
        R
      
    
    
  
 is a strict total order, with a codomain contained in its domain. If 0 is assigned to the lowest type, the type of 
  
    
      
        R
      
    
    
  
 is 3. Infinity can be satisfied only if the (co)domain of 
  
    
      
        R
      
    
    
  
 is infinite, thus forcing the existence of an infinite set. If relations are defined in terms of ordered pairs, this axiom requires a prior definition of ordered pair; the Kuratowski definition, adapted to ST, will do. The literature does not explain why the usual axiom of infinity (there exists an inductive set) of ZFC of other set theories could not be married to ST.
ST reveals how type theory can be made very similar to axiomatic set theory. Moreover, the more elaborate ontology of ST, grounded in what is now called the "iterative conception of set," makes for axiom (schemata) that are far simpler than those of conventional set theories, such as ZFC, with simpler ontologies. Set theories whose point of departure is type theory, but whose axioms, ontology, and terminology differ from the above, include New Foundations and Scott–Potter set theory.

## Related

- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Attribute domain]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bottom type]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ST_type_theory