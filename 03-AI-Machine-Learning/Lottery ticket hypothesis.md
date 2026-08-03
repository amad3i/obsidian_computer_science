---
title: "Lottery ticket hypothesis"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Lottery_ticket_hypothesis"
wikipedia_categories: ["Hypotheses", "Machine learning", "Machine learning stubs"]
related: ["[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Cost-sensitive machine learning]]", "[[Decision list]]", "[[Eager learning]]", "[[Equalized odds]]", "[[Expectation propagation]]", "[[Few-shot learning]]", "[[Hidden layer]]", "[[Inauthentic text]]"]
---

# Lottery ticket hypothesis

In machine learning, the lottery ticket hypothesis is that artificial neural networks with random weights can contain a subnetwork which (entirely by chance) can be tuned to a similar performance as tuning the whole network.

The original statement of the hypothesis is:A randomly-initialized, dense neural network contains a subnetwork that is initialized such that—when trained in isolation—it can match the test accuracy of the original network after training for at most the same number of iterations.The original algorithm is:
Randomily initialize dense network: weights 
  
    
      
        
          θ
          
            0
          
        
      
    
    
  
.
Train for 
  
    
      
        j
      
    
    
  
 iterations → weights 
  
    
      
        
          θ
          
            j
          
        
      
    
    
  
.
Magnitude pruning: build a bitmask 
  
    
      
        m
      
    
    
  
 by setting to 0 the lowest-magnitude weights in each layer (one-shot), or repeat train → prune across rounds to reach higher sparsity (iterative).
Reset surviving weights to initialization: use 
  
    
      
        m
        ⊙
        
          θ
          
            0
          
        
      
    
    
  
 as the starting point. Here 
  
    
      
        ⊙
      
    
    
  
 is elementwise multiplication.
Train the masked network 
  
    
      
        f
        
        
          
            x
            ;
            m
            ⊙
            
              θ
              
                0
              
            
          
        
      
    
    
  
 with the same optimizer, schedule, and data.
Declare "winning ticket" if it achieves comparable test accuracy in 
  
    
      
        ≤
        j
      
    
    
  
 iterations.
The term derived from considering the probability of a tunable subnetwork as the equivalent to a winning lottery ticket; the chance of any given ticket winning is tiny, but if you buy enough of them you are certain to win, and the number of possible subnetworks increases exponentially as the power set of the set of connections, making the number of possible subnetworks astronomical for any reasonably large network.
Such networks are a priori difficult to find, since before training, one does not know which of the exponentially many subnetwork would be "lottery tickets". However, after training, these lottery tickets can be discovered by the pruning algorithm. 
It was found that during the original training of the initial dense network, the weights that would end up in the winning ticket  change a lot, but the other weights change little.  
It was found that if instead of 
  
    
      
        m
        ⊙
        
          θ
          
            0
          
        
      
    
    
  
, they re-sampled a different random initialization 
  
    
      
        
          θ
          
            0
          
          ′
        
      
    
    
  
, and used 
  
    
      
        m
        ⊙
        
          θ
          
            0
          
          ′
        
      
    
    
  
 instead, the trained 
  
    
      
        f
        
        
          
            x
            ;
            m
            ⊙
            
              θ
              
                0
              
              ′
            
          
        
      
    
    
  
 would perform much worse. This indicates that what makes a ticket winning is both its connection graph and the precise initial weights of the connections.

## Related

- [[Astrostatistics]]
- [[Bayesian learning mechanisms]]
- [[Cost-sensitive machine learning]]
- [[Decision list]]
- [[Eager learning]]
- [[Equalized odds]]
- [[Expectation propagation]]
- [[Few-shot learning]]
- [[Hidden layer]]
- [[Inauthentic text]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lottery_ticket_hypothesis