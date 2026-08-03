---
title: "Head grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Head_grammar"
wikipedia_categories: ["Formal languages", "Grammar frameworks", "Syntax"]
related: ["[[Affix grammar]]", "[[Extended affix grammar]]", "[[Categorial grammar]]", "[[Context-free language]]", "[[Context-sensitive grammar]]", "[[Controlled grammar]]", "[[Cross-serial dependencies]]", "[[Discontinuous-constituent phrase structure grammar]]", "[[Formal grammar]]", "[[Generalized context-free grammar]]"]
---

# Head grammar

Head grammar (HG) is a grammar formalism introduced in Carl Pollard (1984) as an extension of the context-free grammar class of grammars. Head grammar is therefore a type of phrase structure grammar, as opposed to a dependency grammar. The class of head grammars is a subset of the linear context-free rewriting systems.
One typical way of defining head grammars is to replace the terminal strings of CFGs with indexed terminal strings, where the index denotes the "head" word of the string. Thus, for example, a CF rule such as 
  
    
      
        A
        →
        a
        b
        c
      
    
    
  
 might instead be 
  
    
      
        A
        →
        a
        b
        c
        ,
        0
      
    
    
  
, where the 0th terminal, the a, is the head of the resulting terminal string. For convenience of notation, such a rule could be written as just the terminal string, with the head terminal denoted by some sort of mark, as in 
  
    
      
        A
        →
        
          
            
              a
              ^
            
          
        
        b
        c
      
    
    
  
.
Two fundamental operations are then added to all rewrite rules: wrapping and concatenation.

## Related

- [[Affix grammar]]
- [[Extended affix grammar]]
- [[Categorial grammar]]
- [[Context-free language]]
- [[Context-sensitive grammar]]
- [[Controlled grammar]]
- [[Cross-serial dependencies]]
- [[Discontinuous-constituent phrase structure grammar]]
- [[Formal grammar]]
- [[Generalized context-free grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Head_grammar