---
title: "Hidden Markov random field"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Hidden_Markov_random_field"
wikipedia_categories: ["Markov networks"]
related: ["[[Factor graph]]", "[[Hammersley–Clifford theorem]]", "[[Markov logic network]]", "[[Markov random field]]", "[[Probabilistic soft logic]]"]
---

# Hidden Markov random field

In statistics, a hidden Markov random field is a generalization of a hidden Markov model.  Instead of having an underlying Markov chain, hidden Markov random fields have an  underlying Markov random field.
Suppose that we observe a random variable 
  
    
      
        
          Y
          
            i
          
        
      
    
    
  
, where 
  
    
      
        i
        ∈
        S
      
    
    
  
. Hidden Markov random fields assume that the probabilistic nature of 
  
    
      
        
          Y
          
            i
          
        
      
    
    
  
 is determined by the unobservable Markov random field 
  
    
      
        
          X
          
            i
          
        
      
    
    
  
, 
  
    
      
        i
        ∈
        S
      
    
    
  
.
That is, given the neighbors 
  
    
      
        
          N
          
            i
          
        
      
    
    
  
 of 
  
    
      
        
          X
          
            i
          
        
        ,
        
          X
          
            i
          
        
      
    
    
  
 is independent of all other 
  
    
      
        
          X
          
            j
          
        
      
    
    
  
 (Markov property).
The main difference with a hidden Markov model is that neighborhood is not defined in 1 dimension but within a network, i.e. 
  
    
      
        
          X
          
            i
          
        
      
    
    
  
 is allowed to have more than the two neighbors that it would have in a Markov chain. The model is formulated in such a way that given 
  
    
      
        
          X
          
            i
          
        
      
    
    
  
, 
  
    
      
        
          Y
          
            i
          
        
      
    
    
  
 are independent (conditional independence of the observable variables given the Markov random field).
In the vast majority of the related literature, the number of possible latent states is considered a user-defined constant. However, ideas from nonparametric Bayesian statistics, which allow for data-driven inference of the number of states, have been also recently investigated with success, e.g.

## Related

- [[Factor graph]]
- [[Hammersley–Clifford theorem]]
- [[Markov logic network]]
- [[Markov random field]]
- [[Probabilistic soft logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hidden_Markov_random_field