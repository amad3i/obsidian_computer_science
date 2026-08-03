---
title: "Uniqueness of identity proofs"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Uniqueness_of_identity_proofs"
wikipedia_categories: ["Mathematical axioms", "Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# Uniqueness of identity proofs

In type theory, uniqueness of identity proofs (UIP) is a possible axiom for dependent type theory which asserts that any two proofs of the same equality are themselves equal. An equivalent and closely related axiom is Streicher's axiom K, which asserts that any proof of an equality 
  
    
      
        x
        x
      
    
    
  
 is equal to the trivial reflexivity proof.
These axioms thus have the respective types:

In intensional type theory with the standard definition of the identity type as an indexed inductive type, UIP and K are unprovable, as first proved by Martin Hoffman and Thomas Streicher using a groupoid model. While this might first seem surprising since the identity type has just one constructor (reflexivity), the apparent contradiction is resolved by the fact that the identity type inductively defines the identity type family 
  
    
      
        x
        ∙
      
    
    
  
 rather than the single type 
  
    
      
        x
        y
      
    
    
  
. According to the identity type's induction principle, given an element 
  
    
      
        x
        :
        X
      
    
    
  
 and a type family 
  
    
      
        C
        :
        
          ∏
          
            y
            :
            X
          
        
        
          ∏
          
            p
            :
            x
            y
          
        
        
          
            T
            y
            p
            e
          
        
      
    
    
  
 as well as an element 
  
    
      
        c
        :
        C
        x
        ,
        
          
            
              r
              e
              f
              l
            
          
          
            x
          
        
      
    
    
  
, we may build a function 
  
    
      
        f
        :
        
          ∏
          
            y
            :
            X
          
        
        
          ∏
          
            p
            :
            x
            y
          
        
        C
        y
        ,
        p
      
    
    
  
 satisfying the definitional equality 
  
    
      
        f
        x
        ,
        
          
            
              r
              e
              f
              l
            
          
          
            x
          
        
        ≡
        c
      
    
    
  
. Informally speaking, the reason why this does not allow to prove, e.g., axiom K, is that the property to be proven should be 
  
    
      
        C
        y
        ,
        p
        :≡
        p
        
          
            
              r
              e
              f
              l
            
          
          
            x
          
        
      
    
    
  
, but this is ill-typed as 
  
    
      
        p
      
    
    
  
 has type 
  
    
      
        x
        y
      
    
    
  
 while 
  
    
      
        
          
            
              r
              e
              f
              l
            
          
          
            x
          
        
      
    
    
  
 has type 
  
    
      
        x
        x
      
    
    
  
.
The axioms UIP and K are equivalent. Indeed, K is a special case of UIP, while UIP can be deduced from K by equality induction on 
  
    
      
        p
      
    
    
  
.
In Martin-Löf's original extensional type theory, UIP and K are provable. This is because extensional type theory includes the so-called equality reflection rule that derives a judgmental equality from a propositional equality, which makes the function 
  
    
      
        C
        y
        ,
        p
        :≡
        p
        
          
            
              r
              e
              f
              l
            
          
          
            x
          
        
      
    
    
  
 well-typed. However, this type theory is not used in practice in proof assistants because it removes parts of proofs from the proof terms.
Martin Hofmann proved that together with functional extensionality, UIP and K in fact sufficient to capture the differences between intensional and extensional Martin-Löf type theory: extensional MLTT is conservative over intensional MLTT with the addition of the axioms of functional extensionality and UIP (or K).
In homotopy type theory, UIP has the interpretation that every type has a trivial homotopical structure where any two paths between the same points are homotopical (equivalently, as in axiom K, all loops are contractible). This is disprovable, as it contradicts the univalence axiom. However, many naturally occurring types 
  
    
      
        X
      
    
    
  
 do satisfy that any two equality proofs between elements of 
  
    
      
        X
      
    
    
  
 are equal. Such types are called sets, or h-sets, or homotopy 0-types, or 0-truncated types.

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

- Wikipedia: https://en.wikipedia.org/wiki/Uniqueness_of_identity_proofs