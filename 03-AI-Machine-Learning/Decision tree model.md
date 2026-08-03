---
title: "Decision tree model"
tags: ["cs", "ai-machine-learning", "advanced"]
domain: AI & Machine Learning
level: advanced
source: "https://en.wikipedia.org/wiki/Decision_tree_model"
wikipedia_categories: ["Computational complexity theory", "Decision trees", "Models of computation"]
related: ["[[Complexity and Real Computation]]", "[[Glossary of quantum computing]]", "[[Model of computation]]", "[[Quantum capacity]]", "[[Quantum computing]]", "[[Transdichotomous model]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Abstract machine]]", "[[Abstract state machine]]", "[[Advice (complexity)]]"]
---

# Decision tree model

In computational complexity theory, the decision tree model is the model of computation in which an algorithm can be considered to be a decision tree, i.e. a sequence of queries or tests that are done adaptively, so the outcome of previous tests can influence the tests performed next.
Typically, these tests have a small number of outcomes (such as a yes–no question) and can be performed quickly (say, with unit computational cost), so the worst-case time complexity of an algorithm in the decision tree model corresponds to the depth of the corresponding tree. This notion of computational complexity of a problem or an algorithm in the decision tree model is called its decision tree complexity or query complexity.
Decision tree models are instrumental in establishing lower bounds for the complexity of certain classes of computational problems and algorithms. Several variants of decision tree models have been introduced, depending on the computational model and type of query algorithms are allowed to perform.
For example, a decision tree argument is used to show that a comparison sort of 
  
    
      
        n
      
    
    
  
 items must make 
  
    
      
        n
         
        n
      
    
    
  
 comparisons. For comparison sorts, a query is a comparison of two items 
  
    
      
        a
        ,
        b
      
    
    
  
, with two outcomes (assuming no items are equal): either 
  
    
      
        a
        b
      
    
    
  
 or 
  
    
      
        a
        b
      
    
    
  
. Comparison sorts can be expressed as decision trees in this model, since such sorting algorithms only perform these types of queries.

## Related

- [[Complexity and Real Computation]]
- [[Glossary of quantum computing]]
- [[Model of computation]]
- [[Quantum capacity]]
- [[Quantum computing]]
- [[Transdichotomous model]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Abstract machine]]
- [[Abstract state machine]]
- [[Advice (complexity)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Decision_tree_model