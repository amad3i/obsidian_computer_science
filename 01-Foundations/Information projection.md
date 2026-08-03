---
title: "Information projection"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Information_projection"
wikipedia_categories: ["Information theory", "Probability stubs"]
related: ["[[Krichevsky–Trofimov estimator]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Adversarial queueing network]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]"]
---

# Information projection

In information theory, the information projection or I-projection of a probability distribution q onto a set of distributions P is

  
    
      
        
          p
          
          
        
        
          
            
              arg
               
              min
            
            
              p
              ∈
              P
            
          
        
        
          D
          
            
              K
              L
            
          
        
         
        p
        
          |
        
        
          |
        
        q
      
    
    
  
.
where 
  
    
      
        
          D
          
            
              K
              L
            
          
        
      
    
    
  
 is the Kullback–Leibler divergence from q to p. Viewing the Kullback–Leibler divergence as a measure of distance, the I-projection 
  
    
      
        
          p
          
          
        
      
    
    
  
 is the "closest" distribution to q of all the distributions in P.
The I-projection is useful in setting up information geometry, notably because of the following inequality, valid when P is convex:

  
    
      
        
          D
          
            
              K
              L
            
          
        
         
        p
        
          |
        
        
          |
        
        q
        ≥
        
          D
          
            
              K
              L
            
          
        
         
        p
        
          |
        
        
          |
        
        
          p
          
          
        
        +
        
          D
          
            
              K
              L
            
          
        
         
        
          p
          
          
        
        
          |
        
        
          |
        
        q
      
    
    
  
.
This inequality can be interpreted as an information-geometric version of Pythagoras' triangle-inequality theorem, where KL divergence is viewed as squared distance in a Euclidean space.
It is worthwhile to note that since 
  
    
      
        
          D
          
            
              K
              L
            
          
        
         
        p
        
          |
        
        
          |
        
        q
        ≥
        0
      
    
    
  
 and continuous in p, 
if P is closed and non-empty, then there exists at least one minimizer to the optimization problem framed above. Furthermore, if P is convex, then the optimum distribution is unique.
The reverse I-projection also known as moment projection or M-projection is

  
    
      
        
          p
          
          
        
        
          
            
              arg
               
              min
            
            
              p
              ∈
              P
            
          
        
        
          D
          
            
              K
              L
            
          
        
         
        q
        
          |
        
        
          |
        
        p
      
    
    
  
.
Since the KL divergence is not symmetric in its arguments, the I-projection and the M-projection will exhibit different behavior. For I-projection, 
  
    
      
        p
        x
      
    
    
  
 will typically
under-estimate the support of 
  
    
      
        q
        x
      
    
    
  
 and will lock onto one of its modes. This is due to 
  
    
      
        p
        x
        =
        0
      
    
    
  
, whenever 
  
    
      
        q
        x
        =
        0
      
    
    
  
 to make sure KL divergence stays finite. For M-projection, 
  
    
      
        p
        x
      
    
    
  
 will typically over-estimate the support of 
  
    
      
        q
        x
      
    
    
  
. This is due to 
  
    
      
        p
        x
        >
        0
      
    
    
  
 whenever 
  
    
      
        q
        x
        >
        0
      
    
    
  
 to make sure KL divergence stays finite. 
The reverse I-projection plays a fundamental role in the construction of optimal e-variables.  

The concept of information projection can be extended to arbitrary f-divergences and other divergences.

## Related

- [[Krichevsky–Trofimov estimator]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Adversarial queueing network]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Information_projection