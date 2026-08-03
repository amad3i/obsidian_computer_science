---
title: "Mathematical induction"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Mathematical_induction"
wikipedia_categories: ["Mathematical induction", "Mathematical logic", "Methods of proof"]
related: ["[[Proof of impossibility]]", "[[Structural induction]]", "[[Absoluteness (logic)]]", "[[Abstract logic]]", "[[Abstract model theory]]", "[[Algebraic semantics (mathematical logic)]]", "[[Algebraic theory]]", "[[Algorithm]]", "[[Algorithmic technique]]", "[[Archive for Mathematical Logic]]"]
---

# Mathematical induction

Mathematical induction is a method for proving that a statement 
  
    
      
        P
        n
      
    
    
  
 is true for every natural number 
  
    
      
        n
      
    
    
  
, that is, that the infinitely many cases 
  
    
      
        P
        0
        ,
        P
        1
        ,
        P
        2
        ,
        P
        3
        ,
        …
      
    
    
  
  all hold. This is done by first proving a simple case, then also showing that if we assume the claim is true for a given case, then the next case is also true. Informal metaphors help to explain this technique, such as falling dominoes or climbing a ladder:

Mathematical induction proves that we can climb as high as we like on a ladder, by proving that we can climb onto the bottom rung (the basis) and that from each rung we can climb up to the next one (the step).
A proof by induction consists of two cases. The first, the base case, proves the statement for 
  
    
      
        n
        0
      
    
    
  
 without assuming any knowledge of other cases. The second case, the induction step, proves that if the statement holds for any given case 
  
    
      
        n
        k
      
    
    
  
, then it must also hold for the next case 
  
    
      
        n
        k
        1
      
    
    
  
. These two steps establish that the statement holds for every natural number 
  
    
      
        n
      
    
    
  
. The base case does not necessarily begin with 
  
    
      
        n
        0
      
    
    
  
, but often with 
  
    
      
        n
        1
      
    
    
  
, and possibly with any fixed natural number 
  
    
      
        n
        N
      
    
    
  
, establishing the truth of the statement for all natural numbers 
  
    
      
        n
        ≥
        N
      
    
    
  
.
The method can be extended to prove statements about more general well-founded structures, such as trees; this generalization, known as structural induction, is used in mathematical logic and computer science. Mathematical induction in this extended sense is closely related to recursion. Mathematical induction is an inference rule used in formal proofs, and is the foundation of most correctness proofs for computer programs.
Despite its name, mathematical induction differs fundamentally from inductive reasoning as used in philosophy, in which the examination of many cases results in a probable conclusion. The mathematical method examines infinitely many cases to prove a general statement, but it does so by a finite chain of deductive reasoning involving the variable 
  
    
      
        n
      
    
    
  
, which can take infinitely many values. The result is a rigorous proof of the statement, not an assertion of its probability.

## Related

- [[Proof of impossibility]]
- [[Structural induction]]
- [[Absoluteness (logic)]]
- [[Abstract logic]]
- [[Abstract model theory]]
- [[Algebraic semantics (mathematical logic)]]
- [[Algebraic theory]]
- [[Algorithm]]
- [[Algorithmic technique]]
- [[Archive for Mathematical Logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mathematical_induction