---
title: "Smallest grammar problem"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Smallest_grammar_problem"
wikipedia_categories: ["Algorithms and data structures stubs", "Data compression", "Formal languages", "NP-complete problems"]
related: ["[[Longest repeated substring problem]]", "[[Shortest common supersequence]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[1-in-3-SAT]]", "[[3-dimensional matching]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]"]
---

# Smallest grammar problem

In data compression and the theory of formal languages, the smallest grammar problem is the problem of finding the smallest context-free grammar that generates a given string of characters (but no other string). The size of a grammar is defined by some authors as the number of symbols on the right side of the production rules.
Others also add the number of rules to that. A grammar that generates only a single string, as required for the solution to this problem, is called a straight-line grammar.
Every binary string of length 
  
    
      
        n
      
    
    
  
 has a grammar of length 
  
    
      
        O
        n
        
          /
        
         
        n
      
    
    
  
, as expressed using big O notation. For binary de Bruijn sequences, no better length is possible.
The (decision version of the) smallest grammar problem is NP-complete.
It can be approximated in polynomial time to within a logarithmic approximation ratio; more precisely, the ratio is 
  
    
      
        O
        log
         
        
          
            
              n
              g
            
          
        
      
    
    
  
 where 
  
    
      
        n
      
    
    
  
 is the length of the given string and 
  
    
      
        g
      
    
    
  
 is the size of its smallest grammar. It is hard to approximate to within a constant approximation ratio. An improvement of the approximation ratio to 
  
    
      
        o
        log
         
        n
        
          /
        
         
         
        n
      
    
    
  
 would also improve certain algorithms for approximate addition chains.

## Related

- [[Longest repeated substring problem]]
- [[Shortest common supersequence]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[1-in-3-SAT]]
- [[3-dimensional matching]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smallest_grammar_problem