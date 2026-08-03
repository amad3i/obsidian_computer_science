---
title: "Version space learning"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Version_space_learning"
wikipedia_categories: ["Machine learning"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Version space learning

Version space learning is a logical approach to machine learning, specifically binary classification. Version space learning algorithms search a predefined space of hypotheses, viewed as a set of logical sentences. Formally, the hypothesis space is a disjunction

  
    
      
        
          H
          
            1
          
        
        ∨
        
          H
          
            2
          
        
        ∨
        .
        .
        .
        ∨
        
          H
          
            n
          
        
      
    
    
  

(i.e., one or more of hypotheses 1 through n are true). A version space learning algorithm is presented with examples, which it will use to restrict its hypothesis space; for each example x, the hypotheses that are inconsistent with x are removed from the space. This iterative refining of the hypothesis space is called the candidate elimination algorithm, the hypothesis space maintained inside the algorithm, its version space.

## Related

- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]
- [[Algorithm selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Version_space_learning