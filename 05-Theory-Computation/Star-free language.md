---
title: "Star-free language"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Star-free_language"
wikipedia_categories: ["Automata (computation)", "Formal languages", "Logic in computer science", "Theoretical computer science stubs"]
related: ["[[Generalized star-height problem]]", "[[Ranked alphabet]]", "[[Abstract rewriting system]]", "[[Computation tree logic]]", "[[Conference on Implementation and Application of Automata]]", "[[Dershowitz–Manna ordering]]", "[[Deterministic automaton]]", "[[Deterministic pushdown automaton]]", "[[Finite thickness]]", "[[Formal grammar]]"]
---

# Star-free language

In theoretical computer science and formal language theory, a regular language is said to be star-free if it can be described by a regular expression constructed from the letters of the alphabet, the empty word, the empty set symbol, all boolean operators – including complementation – and concatenation but no Kleene star. The condition is equivalent to having generalized star height zero.
For instance, the language 
  
    
      
        
          Σ
          
          
        
      
    
    
  
 of all finite words over an alphabet 
  
    
      
        Σ
      
    
    
  
 can be shown to be star-free by taking the complement of the empty set, 
  
    
      
        
          Σ
          
          
        
        
          
            
              ∅
              ¯
            
          
        
      
    
    
  
. Then, the language of words over the alphabet 
  
    
      
        a
        ,
        
        b
      
    
    
  
 that do not have consecutive a's can be defined as 
  
    
      
        
          
            
              
                Σ
                
                
              
              a
              a
              
                Σ
                
                
              
            
            ¯
          
        
      
    
    
  
, first constructing the language of words consisting of 
  
    
      
        a
        a
      
    
    
  
 with an arbitrary prefix and suffix, and then taking its complement, which must be all words which do not contain the substring 
  
    
      
        a
        a
      
    
    
  
.
An example of a regular language which is not star-free is 
  
    
      
        a
        a
        
          
          
        
      
    
    
  
, i.e. the language of strings consisting of an even number of "a". For 
  
    
      
        a
        b
        
          
          
        
      
    
    
  
 where 
  
    
      
        a
        ≠
        b
      
    
    
  
, the language can be defined as 
  
    
      
        
          Σ
          
          
        
        ∖
        b
        
          Σ
          
          
        
        ∪
        
          Σ
          
          
        
        a
        ∪
        
          Σ
          
          
        
        a
        a
        
          Σ
          
          
        
        ∪
        
          Σ
          
          
        
        b
        b
        
          Σ
          
          
        
      
    
    
  
, taking the set of all words and removing from it words starting with 
  
    
      
        b
      
    
    
  
, ending in 
  
    
      
        a
      
    
    
  
 or containing 
  
    
      
        a
        a
      
    
    
  
 or 
  
    
      
        b
        b
      
    
    
  
. However, when 
  
    
      
        a
        b
      
    
    
  
, this definition does not create  
  
    
      
        a
        a
        
          
          
        
      
    
    
  
.
Marcel-Paul Schützenberger characterized star-free languages as those with aperiodic syntactic monoids.  They can also be characterized logically as languages definable in FO[<], the first-order logic over the natural numbers with the less-than relation, as languages accepted by some aperiodic finite-state automaton (known as counter-free languages), and as languages definable in linear temporal logic.
All star-free languages are in uniform AC0.
It takes non-elementary time to decide whether a star-free language over two letters is 
The emptiness problem of starfree language says:

Input: a string in the symbols of 
  
    
      
        a
        ,
        
        b
      
    
    
  
, empty set, concatenation, union, intersection, and complement.
Output: Whether this language contains any element.
This problem is decidable, but only in nonelementary time. As immediate corollaries, it is decidable but nonelementary to decide whether two starfree languages are equal, are disjoint, or contain one another.

## Related

- [[Generalized star-height problem]]
- [[Ranked alphabet]]
- [[Abstract rewriting system]]
- [[Computation tree logic]]
- [[Conference on Implementation and Application of Automata]]
- [[Dershowitz–Manna ordering]]
- [[Deterministic automaton]]
- [[Deterministic pushdown automaton]]
- [[Finite thickness]]
- [[Formal grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Star-free_language