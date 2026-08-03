---
title: "Fano's inequality"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fano's_inequality"
wikipedia_categories: ["Inequalities (mathematics)", "Information theory"]
related: ["[[Entropic uncertainty]]", "[[Inequalities in information theory]]", "[[Log sum inequality]]", "[[Shearer's inequality]]", "[[Z-channel (information theory)]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]"]
---

# Fano's inequality

In information theory, Fano's inequality (also known as the Fano converse and the Fano lemma) relates the average information lost in a noisy channel to the probability of the categorization error.  It was derived by Robert Fano in the early 1950s while teaching a Ph.D. seminar in information theory at MIT, and later recorded in his 1961 textbook.
It is used to find a lower bound on the error probability of any decoder as well as the lower bounds for minimax risks in density estimation.
Let the discrete random variables 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 represent input and output messages with a joint probability 
  
    
      
        P
        x
        ,
        y
      
    
    
  
. Let 
  
    
      
        e
      
    
    
  
 represent an occurrence of error; i.e., that 
  
    
      
        X
        ≠
        
          
            
              X
              ~
            
          
        
      
    
    
  
, with 
  
    
      
        
          
            
              X
              ~
            
          
        
        f
        Y
      
    
    
  
 being an approximate version of 
  
    
      
        X
      
    
    
  
. Fano's inequality is

  
    
      
        H
        X
        ∣
        Y
        ≤
        
          H
          
            b
          
        
        e
        +
        P
        e
        log
         
        
          |
        
        
          
            X
          
        
        
          |
        
        1
        ,
      
    
    
  

where 
  
    
      
        
          
            X
          
        
      
    
    
  
 denotes the support of 
  
    
      
        X
      
    
    
  
, 
  
    
      
        
          |
        
        
          
            X
          
        
        
          |
        
      
    
    
  
 denotes the cardinality of (number of elements in) 
  
    
      
        
          
            X
          
        
      
    
    
  
,

  
    
      
        H
        X
        ∣
        Y
        =
        
          ∑
          
            i
            ,
            j
          
        
        P
        
          x
          
            i
          
        
        ,
        
          y
          
            j
          
        
        log
         
        P
        
          x
          
            i
          
        
        ∣
        
          y
          
            j
          
        
      
    
    
  

is the conditional entropy,

  
    
      
        P
        e
        =
        P
        X
        ≠
        
          
            
              X
              ~
            
          
        
      
    
    
  

is the probability of the communication error, and

  
    
      
        
          H
          
            b
          
        
        e
        =
        P
        e
        log
         
        P
        e
        −
        1
        P
        e
        )
         
        1
        P
        e
        )
      
    
    
  

is the corresponding binary entropy.

## Related

- [[Entropic uncertainty]]
- [[Inequalities in information theory]]
- [[Log sum inequality]]
- [[Shearer's inequality]]
- [[Z-channel (information theory)]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fano's_inequality