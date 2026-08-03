---
title: "Quotient of a formal language"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Quotient_of_a_formal_language"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Quotient of a formal language

In mathematics and computer science, the right quotient (or simply quotient) of a language 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 with respect to language 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
 is the language consisting of strings 
  
    
      
        w
      
    
    
  
 such that 
  
    
      
        w
        x
      
    
    
  
 is in 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 for some string 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
, where 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
 are defined on the same alphabet 
  
    
      
        Σ
      
    
    
  
. Formally:

  
    
      
        
          L
          
            1
          
        
        
          /
        
        
          L
          
            2
          
        
        {
        w
        ∈
        
          Σ
          
          
        
        ∣
        w
        
          L
          
            2
          
        
        ∩
        
          L
          
            1
          
        
        ≠
        ∅
        =
        w
        ∈
        
          Σ
          
          
        
        ∣
        ∃
        x
        ∈
        
          L
          
            2
          
        
         
        :
         
        w
        x
        ∈
        
          L
          
            1
          
        
      
    
    
  

where 
  
    
      
        
          Σ
          
          
        
      
    
    
  
 is the Kleene star on 
  
    
      
        Σ
      
    
    
  
, 
  
    
      
        w
        
          L
          
            2
          
        
      
    
    
  
 is the language formed by concatenating 
  
    
      
        w
      
    
    
  
 with each element of 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
, and 
  
    
      
        ∅
      
    
    
  
 is the empty set.
In other words, for all strings in 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 that have a suffix in 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
, the suffix (right part of the string) is removed.
Similarly, the left quotient of 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 with respect to 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
 is the language consisting of strings 
  
    
      
        w
      
    
    
  
 such that 
  
    
      
        x
        w
      
    
    
  
 is in 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 for some string 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
. Formally:

  
    
      
        
          L
          
            2
          
        
        ∖
        
          L
          
            1
          
        
        {
        w
        ∈
        
          Σ
          
          
        
        ∣
        
          L
          
            2
          
        
        w
        ∩
        
          L
          
            1
          
        
        ≠
        ∅
        =
        w
        ∈
        
          Σ
          
          
        
        ∣
        ∃
        x
        ∈
        
          L
          
            2
          
        
         
        :
         
        x
        w
        ∈
        
          L
          
            1
          
        
      
    
    
  

In other words, for all strings in 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 that have a prefix in 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
, the prefix (left part of the string) is removed.
Note that the operands of 
  
    
      
        ∖
      
    
    
  
 are in reverse order, so that 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
 precedes 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
.
The right and left quotients of 
  
    
      
        
          L
          
            1
          
        
      
    
    
  
 with respect to 
  
    
      
        
          L
          
            2
          
        
      
    
    
  
 may also be written as 
  
    
      
        
          L
          
            1
          
        
        
          L
          
            2
          
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          L
          
            2
          
          
            1
          
        
        
          L
          
            1
          
        
      
    
    
  
 respectively.

## Related

- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]
- [[Affix grammar]]
- [[Agent Communications Language]]
- [[Algorithmic learning theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quotient_of_a_formal_language