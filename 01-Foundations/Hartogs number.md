---
title: "Hartogs number"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hartogs_number"
wikipedia_categories: ["Cardinal numbers", "Set theory"]
related: ["[[Cantor's diagonal argument]]", "[[Cantor's theorem]]", "[[Cardinality of the continuum]]", "[[Cofinality]]", "[[Easton's theorem]]", "[[Limit cardinal]]", "[[Successor cardinal]]", "[[Tarski's theorem about choice]]", "[[Admissible set]]", "[[Almost]]"]
---

# Hartogs number

In mathematics, specifically in axiomatic set theory, the Hartogs number of a set X is the least ordinal number α such that there is no injection from α into X. In other words, α is the least ordinal such that 
  
    
      
        
          |
        
        α
        
          |
        
        ≰
        
          |
        
        X
        
          |
        
      
    
    
  
 (where |A| denotes the cardinality of a set A). The existence of the Hartogs number of any X can be proved in Zermelo–Fraenkel set theory (ZF) without relying on the axiom of choice. The map taking X to α is sometimes called Hartogs's function.
If X can be well-ordered, then |α| > |X|, since the cardinalities of two well-ordered sets are always comparable. In fact, |α| is the successor cardinal of |X|. Hartogs's function thus plays a role in constructing the aleph numbers, which are all the cardinal numbers of infinite well-orderable sets.
If X cannot be well-ordered, then there cannot be an injection from X to α, so |α| > |X| cannot be true, and thus |α| is incomparable to |X|. Conversely, trichotomy for cardinal numbers (the statement that any two cardinal numbers are comparable) thus implies that every set can be well-ordered, and hence implies the axiom of choice.
The existence of the Hartogs number was proved by Friedrich Hartogs in 1915, using Zermelo set theory alone (that is, without using the axiom of choice or the later-introduced replacement schema of ZF). Since Zermelo set theory does not have canonical representatives for ordinal numbers, in Hartogs's result α is allowed to be any well-ordered set with the appropriate order type, and this result can be proved without the replacement schema. In the usual ZF formalization, the replacement schema is needed to convert this well-ordered set to its von Neumann ordinal.

## Related

- [[Cantor's diagonal argument]]
- [[Cantor's theorem]]
- [[Cardinality of the continuum]]
- [[Cofinality]]
- [[Easton's theorem]]
- [[Limit cardinal]]
- [[Successor cardinal]]
- [[Tarski's theorem about choice]]
- [[Admissible set]]
- [[Almost]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hartogs_number