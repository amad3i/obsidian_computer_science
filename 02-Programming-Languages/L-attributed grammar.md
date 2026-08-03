---
title: "L-attributed grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/L-attributed_grammar"
wikipedia_categories: ["Compiler construction", "Formal languages"]
related: ["[[Affix grammar]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Compiler Description Language]]", "[[Context-free grammar]]", "[[ECLR-attributed grammar]]", "[[Extended Backus–Naur form]]", "[[LR-attributed grammar]]", "[[S-attributed grammar]]", "[[Van Wijngaarden grammar]]"]
---

# L-attributed grammar

L-attributed grammars are a special type of attribute grammars. They allow the attributes to be evaluated in one depth-first left-to-right traversal of the abstract syntax tree. As a result, attribute evaluation in L-attributed grammars can be incorporated conveniently in top-down parsing. 
A syntax-directed definition is L-attributed if each inherited attribute of 
  
    
      
        
          X
          
            j
          
        
      
    
    
  
 on the right side of 
  
    
      
        A
        →
        
          X
          
            1
          
        
        ,
        
          X
          
            2
          
        
        ,
        …
        ,
        
          X
          
            n
          
        
      
    
    
  
 depends only on 

the attributes of the symbols 
  
    
      
        
          X
          
            1
          
        
        ,
        
          X
          
            2
          
        
        ,
        …
        ,
        
          X
          
            j
            1
          
        
      
    
    
  

the inherited attributes of 
  
    
      
        A
      
    
    
  
 (but not its synthesized attributes)
Every S-attributed syntax-directed definition is also L-attributed.
Implementing L-attributed definitions in Bottom-Up parsers requires rewriting L-attributed definitions into translation schemes.
Many programming languages are L-attributed. Special types of compilers, the narrow compilers, are based on some form of L-attributed grammar. These are a strict superset of S-attributed grammars. Used for code synthesis.
Either "inherited attributes" or "synthesized attributes" associated with the occurrence of symbol 
  
    
      
        
          X
          
            1
          
        
        ,
        
          X
          
            2
          
        
        ,
        …
        ,
        
          X
          
            n
          
        
      
    
    
  
.

## Related

- [[Affix grammar]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Compiler Description Language]]
- [[Context-free grammar]]
- [[ECLR-attributed grammar]]
- [[Extended Backus–Naur form]]
- [[LR-attributed grammar]]
- [[S-attributed grammar]]
- [[Van Wijngaarden grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/L-attributed_grammar