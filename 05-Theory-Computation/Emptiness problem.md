---
title: "Emptiness problem"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Emptiness_problem"
wikipedia_categories: ["Computer science stubs", "Formal languages", "PSPACE-complete problems", "Polynomial-time problems", "Undecidable problems"]
related: ["[[Cyclic language]]", "[[Equivalence problem]]", "[[Maximal pair]]", "[[Mortality (computability theory)]]", "[[3SUM]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]"]
---

# Emptiness problem

In theoretical computer science and formal language theory, a formal language is empty if its set of valid sentences is the empty set. The emptiness problem is the question of determining whether a language is empty given some representation of it, such as a finite-state automaton. For an automaton having 
  
    
      
        n
      
    
    
  
 states, this is a decision problem that can be solved in 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    
  
 time, or in time 
  
    
      
        O
        n
        m
      
    
    
  
 if the automaton has n states and m transitions. However, variants of that question, such as the emptiness problem for non-erasing stack automata, are PSPACE-complete. The emptiness problem in machine learning and formal languages determines if a model or automaton generates the empty language, which is undecidable for certain alternating multi-head finite automata over single-letter alphabets.
The emptiness problem is undecidable for context-sensitive grammars, a fact that follows from the undecidability of the halting problem. It is, however, decidable for context-free grammars.

## Related

- [[Cyclic language]]
- [[Equivalence problem]]
- [[Maximal pair]]
- [[Mortality (computability theory)]]
- [[3SUM]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Emptiness_problem