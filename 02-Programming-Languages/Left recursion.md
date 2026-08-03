---
title: "Left recursion"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Left_recursion"
wikipedia_categories: ["Control flow", "Formal languages", "Parsing", "Recursion"]
related: ["[[Attribute grammar]]", "[[Definite clause grammar]]", "[[Extended affix grammar]]", "[[Lexical grammar]]", "[[Parser combinator]]", "[[Recursive language]]", "[[Syntactic predicate]]", "[[Van Wijngaarden grammar]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]"]
---

# Left recursion

In the formal language theory of computer science, left recursion is a special case of recursion where a string is recognized as part of a language by the fact that it decomposes into a string from that same language (on the left) and a suffix (on the right).  For instance, 
  
    
      
        1
        2
        3
      
    
    
  
 can be recognized as a sum because it can be broken into 
  
    
      
        1
        2
      
    
    
  
, also a sum, and 
  
    
      
        

        
        3
      
    
    
  
, a suitable suffix.
In terms of context-free grammar, a nonterminal is left-recursive if the leftmost symbol in one of its productions is itself (in the case of direct left recursion) or can be made itself by some sequence of substitutions (in the case of indirect left recursion).

## Related

- [[Attribute grammar]]
- [[Definite clause grammar]]
- [[Extended affix grammar]]
- [[Lexical grammar]]
- [[Parser combinator]]
- [[Recursive language]]
- [[Syntactic predicate]]
- [[Van Wijngaarden grammar]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Left_recursion