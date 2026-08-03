---
title: "Semi-Thue system"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Semi-Thue_system"
wikipedia_categories: ["Formal languages", "Rewriting systems", "Theory of computation"]
related: ["[[Abstract rewriting system]]", "[[Dershowitz–Manna ordering]]", "[[Markov algorithm]]", "[[Normal form (abstract rewriting)]]", "[[Omega language]]", "[[Recursive language]]", "[[Recursively enumerable language]]", "[[Rewriting]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]"]
---

# Semi-Thue system

In theoretical computer science and mathematical logic a string rewriting system (SRS), historically called a semi-Thue system, is a rewriting system over strings from a (usually finite) alphabet. Given a binary relation 
  
    
      
        R
      
    
    
  
 between fixed strings over the alphabet, called rewrite rules, denoted by 
  
    
      
        s
        →
        t
      
    
    
  
, an SRS extends the rewriting relation to all strings in which the left- and right-hand side of the rules appear as substrings, that is 
  
    
      
        u
        s
        v
        →
        u
        t
        v
      
    
    
  
, where 
  
    
      
        s
      
    
    
  
, 
  
    
      
        t
      
    
    
  
, 
  
    
      
        u
      
    
    
  
, and 
  
    
      
        v
      
    
    
  
 are strings.
The notion of a semi-Thue system essentially coincides with the presentation of a monoid. Thus they constitute a natural framework for solving the word problem for monoids and groups.
An SRS can be defined directly as an abstract rewriting system. It can also be seen as a restricted kind of a term rewriting system, in which all function symbols have an arity of at most 1. As a formalism, string rewriting systems are Turing complete. The semi-Thue name comes from the Norwegian mathematician Axel Thue, who introduced systematic treatment of string rewriting systems in a 1914 paper. Thue introduced this notion hoping to solve the word problem for finitely presented semigroups. Only in 1947 was the problem shown to be undecidable— this result was obtained independently by Emil Post and A. A. Markov Jr.

## Related

- [[Abstract rewriting system]]
- [[Dershowitz–Manna ordering]]
- [[Markov algorithm]]
- [[Normal form (abstract rewriting)]]
- [[Omega language]]
- [[Recursive language]]
- [[Recursively enumerable language]]
- [[Rewriting]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semi-Thue_system