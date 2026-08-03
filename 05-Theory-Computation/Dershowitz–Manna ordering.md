---
title: "Dershowitz–Manna ordering"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Dershowitz–Manna_ordering"
wikipedia_categories: ["Formal languages", "Logic in computer science", "Rewriting systems"]
related: ["[[Abstract rewriting system]]", "[[Normal form (abstract rewriting)]]", "[[Rewriting]]", "[[Semi-Thue system]]", "[[Star-free language]]", "[[Unification (computer science)]]", "[[1-in-3-SAT]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract semantic graph]]"]
---

# Dershowitz–Manna ordering

In mathematics, the Dershowitz–Manna ordering is a well-founded ordering on multisets named after Nachum Dershowitz and Zohar Manna. It is often used in context of termination of programs or term rewriting systems.
Suppose that 
  
    
      
        S
        ,
        
          
            S
          
        
      
    
    
  
 is a well-founded partial order and let 
  
    
      
        
          
            M
          
        
        S
      
    
    
  
 be the set of all finite multisets on 
  
    
      
        S
      
    
    
  
. For multisets 
  
    
      
        M
        ,
        N
        ∈
        
          
            M
          
        
        S
      
    
    
  
 we define the Dershowitz–Manna ordering 
  
    
      
        M
        
          
            D
            M
          
        
        N
      
    
    
  
 as follows:

  
    
      
        M
        
          
            D
            M
          
        
        N
      
    
    
  
 whenever there exist two multisets 
  
    
      
        X
        ,
        Y
        ∈
        
          
            M
          
        
        S
      
    
    
  
 with the following properties:

  
    
      
        X
        ≠
        ∅
      
    
    
  
,

  
    
      
        X
        ⊆
        N
      
    
    
  
,

  
    
      
        M
        (
        N
        X
        +
        Y
      
    
    
  
, and

  
    
      
        X
      
    
    
  
 dominates 
  
    
      
        Y
      
    
    
  
, that is, for all  
  
    
      
        y
        ∈
        Y
      
    
    
  
, there is some 
  
    
      
        x
        ∈
        X
      
    
    
  
 such that 
  
    
      
        y
        
          
            S
          
        
        x
      
    
    
  
.
An equivalent definition was given by Huet and Oppen as follows:

  
    
      
        M
        
          
            D
            M
          
        
        N
      
    
    
  
 if and only if 

  
    
      
        M
        ≠
        N
      
    
    
  
, and
for all 
  
    
      
        y
      
    
    
  
 in 
  
    
      
        S
      
    
    
  
, if 
  
    
      
        M
        y
        >
        N
        y
      
    
    
  
 then there is some 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        S
      
    
    
  
 such that 
  
    
      
        y
        
          
            S
          
        
        x
      
    
    
  
 and 
  
    
      
        M
        x
        <
        N
        x
      
    
    
  
.

## Related

- [[Abstract rewriting system]]
- [[Normal form (abstract rewriting)]]
- [[Rewriting]]
- [[Semi-Thue system]]
- [[Star-free language]]
- [[Unification (computer science)]]
- [[1-in-3-SAT]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract semantic graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dershowitz–Manna_ordering