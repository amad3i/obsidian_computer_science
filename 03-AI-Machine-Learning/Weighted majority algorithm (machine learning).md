---
title: "Weighted majority algorithm (machine learning)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Weighted_majority_algorithm_(machine_learning)"
wikipedia_categories: ["Machine learning algorithms"]
related: ["[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Augmented Analytics]]", "[[Backpropagation]]", "[[Bootstrap aggregating]]", "[[CN2 algorithm]]", "[[Co-training]]", "[[Constructing skill trees]]"]
---

# Weighted majority algorithm (machine learning)

In machine learning, weighted majority algorithm (WMA) is a meta learning algorithm used  to construct a compound algorithm from a pool of prediction algorithms, which could be any type of learning algorithms, classifiers, or even real human experts.
The algorithm assumes that we have no prior knowledge about the accuracy of the algorithms in the pool, but there are sufficient reasons to believe that one or more will perform well.
Assume that the problem is a binary decision problem. To construct the compound algorithm, a positive weight is given to each of the algorithms in the pool. The compound algorithm then collects weighted votes from all the algorithms in the pool, and gives the prediction that has a higher vote. If the compound algorithm makes a mistake, the algorithms in the pool that contributed to the wrong predicting will be discounted by a certain ratio β where 0<β<1.
It can be shown that the upper bounds on the number of mistakes made in a given sequence of predictions from a pool of algorithms 
  
    
      
        
          A
        
      
    
    
  
 is

  
    
      
        
          O
          l
          o
          g
          
            |
          
          A
          
            |
          
          m
        
      
    
    
  

if one algorithm in 
  
    
      
        
          
            x
          
          
            i
          
        
      
    
    
  
 makes at most 
  
    
      
        
          m
        
      
    
    
  
 mistakes.
There are many variations of the weighted majority algorithm to handle different situations, like shifting targets, infinite pools, or randomized predictions. The core mechanism remains similar, with the final performances of the compound algorithm bounded by a function of the performance of the specialist (best performing algorithm) in the pool.

## Related

- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Augmented Analytics]]
- [[Backpropagation]]
- [[Bootstrap aggregating]]
- [[CN2 algorithm]]
- [[Co-training]]
- [[Constructing skill trees]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weighted_majority_algorithm_(machine_learning)