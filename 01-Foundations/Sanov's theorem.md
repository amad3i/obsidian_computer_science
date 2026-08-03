---
title: "Sanov's theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sanov's_theorem"
wikipedia_categories: ["Information theory"]
related: ["[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]", "[[Bandwidth extension]]", "[[Bar product]]"]
---

# Sanov's theorem

In mathematics and information theory, Sanov's theorem gives a bound on the probability of observing an atypical sequence of samples from a given probability distribution. In the language of large deviations theory, Sanov's theorem identifies the rate function for large deviations of the empirical measure of a sequence of i.i.d. random variables.
Let A be a set of probability distributions over an alphabet X, and let q be an arbitrary distribution over X (where q may or may not be in A).  Suppose we draw n i.i.d. samples from q, represented by the vector 
  
    
      
        
          x
          
            n
          
        
        (
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
      
    
    
  
.  Then, we have the following bound on the probability that the empirical measure 
  
    
      
        
          
            
              
                p
                ^
              
            
          
          
            
              x
              
                n
              
            
          
        
      
    
    
  
 of the samples falls within the set A:

  
    
      
        
          q
          
            n
          
        
        
          
            
              
                p
                ^
              
            
          
          
            
              x
              
                n
              
            
          
        
        ∈
        A
        ≤
        n
        1
        
          
            
              |
            
            X
            
              |
            
          
        
        
          2
          
            n
            
              D
              
                
                  K
                  L
                
              
            
            
              p
              
              
            
            
              |
            
            
              |
            
            q
          
        
      
    
    
  
,
where

  
    
      
        
          q
          
            n
          
        
      
    
    
  
 is the joint probability distribution on 
  
    
      
        
          X
          
            n
          
        
      
    
    
  
, and

  
    
      
        
          p
          
          
        
      
    
    
  
 is the information projection of q onto A.

  
    
      
        
          D
          
            
              K
              L
            
          
        
        P
        ‖
        Q
      
    
    
  
, the KL divergence, is given by: 
  
    
      
        
          D
          
            
              K
              L
            
          
        
        P
        ‖
        Q
        =
        
          ∑
          
            x
            ∈
            
              
                X
              
            
          
        
        P
        x
        log
         
        
          
            
              P
              x
            
            
              Q
              x
            
          
        
        .
      
    
    
  

In words, the probability of drawing an atypical distribution is bounded by a function of the KL divergence from the true distribution to the atypical one; in the case that we consider a set of possible atypical distributions, there is a dominant atypical distribution, given by the information projection.
Furthermore, if A is a closed set, then

  
    
      
        
          
            n
            →
            ∞
          
        
        
          
            1
            n
          
        
         
        
          q
          
            n
          
        
        
          
            
              
                p
                ^
              
            
          
          
            
              x
              
                n
              
            
          
        
        ∈
        A
        =
        
          D
          
            
              K
              L
            
          
        
        
          p
          
          
        
        
          |
        
        
          |
        
        q
        .
      
    
    

## Related

- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]
- [[Bandwidth extension]]
- [[Bar product]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sanov's_theorem