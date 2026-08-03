---
title: "Greibach normal form"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Greibach_normal_form"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Greibach normal form

In formal language theory, a context-free grammar is in Greibach normal form (GNF) if the right-hand sides of all production rules start with a terminal symbol, optionally followed by some non-terminals. A non-strict form allows one exception to this format restriction for allowing the empty word (epsilon, ε) to be a member of the described language. The normal form was established by Sheila Greibach and it bears her name.
More precisely, a context-free grammar is in Greibach normal form, if all production rules are of the form:

  
    
      
        A
        →
        a
        
          A
          
            1
          
        
        
          A
          
            2
          
        
        ⋯
        
          A
          
            n
          
        
      
    
    
  

where 
  
    
      
        A
      
    
    
  
 is a nonterminal symbol, 
  
    
      
        a
      
    
    
  
 is a terminal symbol, and

  
    
      
        
          A
          
            1
          
        
        
          A
          
            2
          
        
        …
        
          A
          
            n
          
        
      
    
    
  
 is a (possibly empty) sequence of nonterminal symbols.
Observe that the grammar does not have left recursions.
Every context-free grammar can be transformed into an equivalent grammar in Greibach normal form. Various constructions exist. Some do not permit the second form of rule and cannot transform context-free grammars that can generate the empty word. For one such construction the size of the constructed grammar is O(n4) in the general case and O(n3) if no derivation of the original grammar consists of a single nonterminal symbol, where n is the size of the original grammar. This conversion can be used to prove that every context-free language can be accepted by a real-time (non-deterministic) pushdown automaton, i.e., the automaton reads a letter from its input every step.
Given a grammar in GNF and a derivable string in the grammar with length n, any top-down parser will halt at depth n.

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

- Wikipedia: https://en.wikipedia.org/wiki/Greibach_normal_form