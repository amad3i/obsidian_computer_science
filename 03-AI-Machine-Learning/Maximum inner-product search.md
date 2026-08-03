---
title: "Maximum inner-product search"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Maximum_inner-product_search"
wikipedia_categories: ["Computational problems", "Machine learning", "Search algorithms"]
related: ["[[Hierarchical navigable small world]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[A- search algorithm]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]"]
---

# Maximum inner-product search

Maximum inner-product search (MIPS) is a search problem, with a corresponding class of search algorithms which attempt to maximise the inner product between a query and the data items to be retrieved. MIPS algorithms are used in a wide variety of big data applications, including recommendation algorithms and machine learning.
Formally, for a database of vectors 
  
    
      
        
          x
          
            i
          
        
      
    
    
  
 defined over a set of labels 
  
    
      
        S
      
    
    
  
 in an inner product space with an inner product 
  
    
      
        ⟨
        ⋅
        ,
        ⋅
        ⟩
      
    
    
  
 defined on it, MIPS search can be defined as the problem of determining

  
    
      
        
          
            
              a
              r
              g
              
              m
              a
              x
            
            
              i
              ∈
              S
            
          
        
         
        ⟨
        
          x
          
            i
          
        
        ,
        q
        ⟩
      
    
    
  

for a given query 
  
    
      
        q
      
    
    
  
.
Although there is an obvious linear-time implementation, it is generally too slow to be used on practical problems. However, efficient algorithms exist to speed up MIPS search.
Under the assumption of all vectors in the set having constant norm,  MIPS can be viewed as equivalent to a nearest neighbor search (NNS) problem in which maximizing the inner product is equivalent to minimizing the corresponding distance metric in the NNS problem. Like other forms of NNS, MIPS algorithms may be approximate or exact.
MIPS search is used as part of DeepMind's RETRO algorithm.

## Related

- [[Hierarchical navigable small world]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[A- search algorithm]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Maximum_inner-product_search