---
title: "Preferential entailment"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Preferential_entailment"
wikipedia_categories: ["Knowledge representation", "Logic in computer science", "Non-classical logic"]
related: ["[[Agentive logic]]", "[[Combs method]]", "[[Computability logic]]", "[[Constructive logic]]", "[[Dynamic logic (modal logic)]]", "[[Event calculus]]", "[[Fuzzy logic]]", "[[Intuitionistic logic]]", "[[1-in-3-SAT]]", "[[4E cognition]]"]
---

# Preferential entailment

Preferential entailment is a non-monotonic logic based on selecting only models that are considered the most plausible. The plausibility of models is expressed by an ordering among models called a preference relation, hence the name preference entailment.
Formally, given a propositional formula 
  
    
      
        F
      
    
    
  
 and an ordering over propositional models 
  
    
      
        ≤
      
    
    
  
, preferential entailment selects only the models of 
  
    
      
        F
      
    
    
  
 that are minimal according to 
  
    
      
        ≤
      
    
    
  
. This selection leads to a non-monotonic inference relation: 
  
    
      
        F
        
          ⊨
          
            pref
          
        
        G
      
    
    
  
 holds if and only if all minimal models of 
  
    
      
        F
      
    
    
  
 according to 
  
    
      
        ≤
      
    
    
  
 are also models of 
  
    
      
        G
      
    
    
  
.
Circumscription can be seen as the particular case of preferential entailment when the ordering is based on containment of the sets of variables assigned to true (in the propositional case) or containment of the extensions of predicates (in the first-order logic case).

## Related

- [[Agentive logic]]
- [[Combs method]]
- [[Computability logic]]
- [[Constructive logic]]
- [[Dynamic logic (modal logic)]]
- [[Event calculus]]
- [[Fuzzy logic]]
- [[Intuitionistic logic]]
- [[1-in-3-SAT]]
- [[4E cognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Preferential_entailment