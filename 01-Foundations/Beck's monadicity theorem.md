---
title: "Beck's monadicity theorem"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Beck's_monadicity_theorem"
wikipedia_categories: ["Adjoint functors", "Category theory"]
related: ["[[Cotriple homology]]", "[[Equivalence of categories]]", "[[Isbell duality]]", "[[Kan extension]]", "[[Monad (category theory)]]", "[[Pseudoalgebra]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[AB5 category]]", "[[Abstract elementary class]]"]
---

# Beck's monadicity theorem

In category theory, a branch of mathematics, Beck's monadicity theorem gives a criterion that characterises monadic functors, introduced by Jonathan Mock Beck (1968). It is often stated in dual form for comonads.  It is sometimes called the Beck tripleability theorem because of the older term triple for a monad.
Beck's monadicity theorem asserts that a functor

  
    
      
        U
        :
        C
        →
        D
      
    
    
  

is monadic if and only if

U has a left adjoint;
U reflects isomorphisms (if U(f) is an isomorphism then so is f); and
C has coequalizers of U-split parallel pairs (those parallel pairs of morphisms in C, which U sends to pairs having a split coequalizer in D), and U preserves those coequalizers.
There are several variations of Beck's theorem: if U has a left adjoint then any of the following conditions ensure that U is monadic:

U reflects isomorphisms and C has coequalizers of reflexive pairs (those with a common right inverse)  and U preserves those coequalizers.  (This gives the crude monadicity theorem.)
Every diagram in C which is by U sent to a split coequalizer sequence in D is itself a coequalizer sequence in C. In different words, U creates (preserves and reflects) U-split coequalizer sequences.
Another variation of Beck's theorem characterizes strictly monadic functors: those for which the comparison functor is an isomorphism rather than just an equivalence of categories. For this version the definitions of what it means to create coequalizers is changed slightly: the coequalizer has to be unique rather than just unique up to isomorphism.
Beck's theorem is particularly important in its relation with the descent theory, which plays a role in sheaf and stack theory, as well as in the Alexander Grothendieck's approach to algebraic geometry. Most cases of faithfully flat descent of algebraic structures (e.g. those in FGA and in  SGA1) are special cases of Beck's theorem. The theorem gives an exact categorical description of the process of 'descent', at this level. In 1970 the Grothendieck approach via fibered categories and descent data was shown (by Jean Bénabou and Jacques Roubaud) to be equivalent (under some conditions) to the comonad approach. In a later work, Pierre Deligne applied Beck's theorem to Tannakian category theory, greatly simplifying the basic developments.
 Linton's monadicity theorem: Let 
  
    
      
        
          
            A
          
        
      
    
    
  
 be a category that has kernel pairs of retractions, and let 
  
    
      
        
          
            C
          
        
      
    
    
  
 be a category that has kernel pairs and coequalizers. Let 
  
    
      
        U
        :
        
          
            C
          
        
        →
        
          
            A
          
        
      
    
    
  
 be functor. When 
  
    
      
        
          
            A
          
        
        
          
            Set
          
        
      
    
    
  
, 
  
    
      
        U
      
    
    
  
 is monadic if and only if

  
    
      
        U
      
    
    
  
 has a left adjoint;

  
    
      
        U
      
    
    
  
 preserves and reflects regular epimorphisms; and

  
    
      
        f
        ,
        g
      
    
    
  
 is kernel pair if and only if 
  
    
      
        
          U
          
            f
          
        
        ,
        
          U
          
            g
          
        
      
    
    
  
 is kernel pair.
Linton (1969) proved this theorem in a more general category, requiring it to be a category 
  
    
      
        
          
            A
          
        
      
    
    
  
 in which every epimorphism splits.

## Related

- [[Cotriple homology]]
- [[Equivalence of categories]]
- [[Isbell duality]]
- [[Kan extension]]
- [[Monad (category theory)]]
- [[Pseudoalgebra]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[AB5 category]]
- [[Abstract elementary class]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Beck's_monadicity_theorem