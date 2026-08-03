---
title: "Concept class"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Concept_class"
wikipedia_categories: ["Computational learning theory"]
related: ["[[Algorithmic learning theory]]", "[[Bondy's theorem]]", "[[Distribution learning theory]]", "[[Error tolerance (PAC learning)]]", "[[Growth function]]", "[[Induction of regular languages]]", "[[Language identification in the limit]]", "[[Occam learning]]", "[[Open weights]]", "[[Probably approximately correct learning]]"]
---

# Concept class

In computational learning theory in mathematics, a concept over a domain X is a total Boolean function over X. A concept class is a class of concepts. Concept classes are a subject of computational learning theory.
Concept class terminology frequently appears in model theory associated with probably approximately correct (PAC) learning. In this setting, if one takes a set Y as a set of (classifier output) labels, and X is a set of examples, the map 
  
    
      
        c
        :
        X
        →
        Y
      
    
    
  
, i.e. from examples to classifier labels (where 
  
    
      
        Y
        {
        0
        ,
        1
      
    
    
  
 and where c is a subset of X), c is then said to be a concept. A concept class 
  
    
      
        C
      
    
    
  
 is then a collection of such concepts.
Given a class of concepts C, a subclass D is reachable if there exists a sample s such that D contains exactly those concepts in C that are extensions to s. Not every subclass is reachable.

## Related

- [[Algorithmic learning theory]]
- [[Bondy's theorem]]
- [[Distribution learning theory]]
- [[Error tolerance (PAC learning)]]
- [[Growth function]]
- [[Induction of regular languages]]
- [[Language identification in the limit]]
- [[Occam learning]]
- [[Open weights]]
- [[Probably approximately correct learning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concept_class