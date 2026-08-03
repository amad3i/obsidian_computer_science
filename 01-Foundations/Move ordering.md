---
title: "Move ordering"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Move_ordering"
wikipedia_categories: ["Computer chess", "Game theory"]
related: ["[[Move generation]]", "[[Nolot]]", "[[Ambiguity aversion]]", "[[Analytic narrative]]", "[[Asynchrony (game theory)]]", "[[Aumann's agreement theorem]]", "[[Authority distribution]]", "[[Backward induction]]", "[[Banzhaf power index]]", "[[Bayesian efficiency]]"]
---

# Move ordering

Move ordering refers to the practice of selecting the most promising moves first during game-tree search (especially in computer chess). In minimax searches with alpha–beta pruning, good move ordering is important, examining stronger moves early causes cutoffs that eliminate subtrees, vastly reducing the number of nodes searched. In the ideal case of perfect move ordering the search complexity drops from 
  
    
      
        O
        
          b
          
            d
          
        
      
    
    
  
 to approximately 
  
    
      
        O
        
          b
          
            d
            
              /
            
            2
          
        
      
    
    
  
, effectively halving the effective branching factor to 
  
    
      
        
          
            b
          
        
      
    
    
  
 and allowing roughly twice the search depth for a given computational effort. Claude Shannon observed that although a typical chess position may have on the order of 30 legal moves, effective pruning and heuristics reduce the useful branching factor to only a few.

## Related

- [[Move generation]]
- [[Nolot]]
- [[Ambiguity aversion]]
- [[Analytic narrative]]
- [[Asynchrony (game theory)]]
- [[Aumann's agreement theorem]]
- [[Authority distribution]]
- [[Backward induction]]
- [[Banzhaf power index]]
- [[Bayesian efficiency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Move_ordering