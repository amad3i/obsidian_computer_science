---
title: "Ranked alphabet"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Ranked_alphabet"
wikipedia_categories: ["Automata (computation)", "Formal languages", "Theoretical computer science", "Theoretical computer science stubs", "Trees (data structures)"]
related: ["[[Tree (automata theory)]]", "[[Tree automaton]]", "[[Tree transducer]]", "[[Generalized star-height problem]]", "[[Random-access Turing machine]]", "[[Regular numerical predicate]]", "[[Star-free language]]", "[[Turing machine]]", "[[Abstract syntax tree]]", "[[Bridging model]]"]
---

# Ranked alphabet

In theoretical computer science and formal language theory, a ranked alphabet is a pair of an ordinary alphabet F and a function Arity: F→
  
    
      
        
          N
        
      
    
    
  
. Each letter in F has its arity so it can be used to build terms. Nullary elements (of zero arity) are also called constants. Terms built with unary symbols and constants can be considered as strings. Higher arities lead to proper trees.
For instance, in the term 

  
    
      
        f
        a
        ,
        g
        a
        ,
        f
        a
        ,
        b
        ,
        c
        )
      
    
    
  
,
a,b,c are constants, g is unary, and f is ternary.
Contrariwise,  

  
    
      
        f
        a
        ,
        f
        a
        )
      
    
    
  

cannot be a valid term, as the symbol f appears once as binary, and once as unary, which is illicit, as Arity must be a function.

## Related

- [[Tree (automata theory)]]
- [[Tree automaton]]
- [[Tree transducer]]
- [[Generalized star-height problem]]
- [[Random-access Turing machine]]
- [[Regular numerical predicate]]
- [[Star-free language]]
- [[Turing machine]]
- [[Abstract syntax tree]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ranked_alphabet