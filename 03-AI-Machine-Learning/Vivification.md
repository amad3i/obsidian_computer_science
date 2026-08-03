---
title: "Vivification"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Vivification"
wikipedia_categories: ["Knowledge representation"]
related: ["[[4E cognition]]", "[[Agent Communications Language]]", "[[Agentive logic]]", "[[AgMES]]", "[[Agricultural Information Management Standards]]", "[[AGROVOC]]", "[[Allen's interval algebra]]", "[[Arabic Ontology]]", "[[Attempto Controlled English]]", "[[Attribute–value system]]"]
---

# Vivification

Vivification is an operation on a description logic knowledge base to improve performance of a semantic reasoner.  Vivification replaces a disjunction of concepts 
  
    
      
        
          C
          
            1
          
        
        ⊔
        
          C
          
            2
          
        
        …
        ⊔
        
          C
          
            n
          
        
      
    
    
  
 by the least common subsumer of the concepts 
  
    
      
        
          C
          
            1
          
        
        ,
        
          C
          
            2
          
        
        ,
        …
        
          C
          
            n
          
        
      
    
    
  
.
The goal of this operation is to improve the performance of the reasoner by replacing a complex set of concepts with a single concept which subsumes the original concepts. 
For example, consider the example given in (Cohen 92):  Suppose we have the concept 
  
    
      
        
          
            PIANIST(Jill)
          
        
        ∨
        
          
            ORGANIST(Jill)
          
        
      
    
    
  
.  This concept can be vivified into a simpler concept 
  
    
      
        
          
            KEYBOARD-PLAYER(Jill)
          
        
      
    
    
  
.  This summarization leads to an approximation that may not be exactly equivalent to the original.

## Related

- [[4E cognition]]
- [[Agent Communications Language]]
- [[Agentive logic]]
- [[AgMES]]
- [[Agricultural Information Management Standards]]
- [[AGROVOC]]
- [[Allen's interval algebra]]
- [[Arabic Ontology]]
- [[Attempto Controlled English]]
- [[Attribute–value system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vivification