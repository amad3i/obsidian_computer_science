---
title: "Forward–backward algorithm"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Forward–backward_algorithm"
wikipedia_categories: ["Dynamic programming", "Error detection and correction", "Machine learning algorithms", "Markov models"]
related: ["[[Viterbi algorithm]]", "[[Diffusion model]]", "[[Dynamic time warping]]", "[[Iterative Viterbi decoding]]", "[[Acknowledgement (data networks)]]", "[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Alternant code]]"]
---

# Forward–backward algorithm

The forward–backward algorithm is an  inference algorithm for hidden Markov models which computes the posterior marginals of all hidden state variables given a sequence of observations/emissions 
  
    
      
        
          o
          
            1
            :
            T
          
        
        :=
        
          o
          
            1
          
        
        ,
        …
        ,
        
          o
          
            T
          
        
      
    
    
  
, i.e. it computes, for all hidden state variables 
  
    
      
        
          X
          
            t
          
        
        ∈
        
          X
          
            1
          
        
        ,
        …
        ,
        
          X
          
            T
          
        
      
    
    
  
, the distribution 
  
    
      
        P
        
          X
          
            t
          
        
         
        
          |
        
         
        
          o
          
            1
            :
            T
          
        
      
    
    
  
. This inference task is usually called smoothing. The algorithm makes use of the principle of dynamic programming to efficiently compute the values that are required to obtain the posterior marginal distributions in two passes. The first pass goes forward in time while the second goes backward in time; hence the name forward–backward algorithm.
The term forward–backward algorithm is also used to refer to any algorithm belonging to the general class of algorithms that operate on sequence models in a forward–backward manner. In this sense, the descriptions in the remainder of this article refer only to one specific instance of this class.

## Related

- [[Viterbi algorithm]]
- [[Diffusion model]]
- [[Dynamic time warping]]
- [[Iterative Viterbi decoding]]
- [[Acknowledgement (data networks)]]
- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Alternant code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Forward–backward_algorithm