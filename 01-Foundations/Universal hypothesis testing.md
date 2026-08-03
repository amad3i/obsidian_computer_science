---
title: "Universal hypothesis testing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Universal_hypothesis_testing"
wikipedia_categories: ["Asymptotic theory (statistics)", "Information theory", "Nonparametric statistics", "Statistical hypothesis testing"]
related: ["[[Error exponents in hypothesis testing]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]", "[[Bandwidth extension]]"]
---

# Universal hypothesis testing

In statistics, universal hypothesis testing is a special case of binary simple hypothesis testing. The universal problem is to distinguish between a simple null hypothesis 
  
    
      
        
          H
          
            0
          
        
        :
        Q
        P
      
    
    
  
, and the most general composite alternative 
  
    
      
        
          H
          
            1
          
        
        :
        Q
        ≠
        P
      
    
    
  
, using independent and identically distributed samples from 
  
    
      
        Q
      
    
    
  
. The setting is sometimes referred to as goodness of fit testing, or one-sample testing. 
A simple binary hypothesis testing problem involves distinguishing between 
  
    
      
        
          H
          
            0
          
        
        :
        Q
        
          P
          
            0
          
        
      
    
    
  
 and 
  
    
      
        
          H
          
            1
          
        
        :
        Q
        
          P
          
            1
          
        
      
    
    
  
, using samples 
  
    
      
        
          X
          
            1
          
        
        ,
        …
        ,
        
          X
          
            n
          
        
        
          
            ∼
            i.i.d.
          
        
        Q
      
    
    
  
. In the traditional setting of hypothesis testing 
  
    
      
        
          P
          
            0
          
        
        ,
        
          P
          
            1
          
        
      
    
    
  
 are known apriori. A composite version of this problem involves sets of probability distributions 
  
    
      
        
          Ω
          
            0
          
        
        ,
        
          Ω
          
            1
          
        
      
    
    
  
, and asks to distinguish between 
  
    
      
        
          H
          
            0
          
        
        :
        Q
        ∈
        
          Ω
          
            0
          
        
      
    
    
  
 and 
  
    
      
        
          H
          
            1
          
        
        :
        Q
        ∈
        
          Ω
          
            1
          
        
      
    
    
  
. In contrast, the universal setting corresponds to the special case of composite hypothesis testing, where the null hypothesis is simple, 
  
    
      
        
          Ω
          
            0
          
        
        P
      
    
    
  
 and the alternative hypothesis is the set of all distributions other than 
  
    
      
        P
      
    
    
  
, 
  
    
      
        
          Ω
          
            1
          
        
        {
        F
        :
        F
        ≠
        P
      
    
    
  
. For example, someone might want to know if a particular coin was fair, i.e. 
  
    
      
        
          P
        
        X
        H
        =
        
          
            1
            2
          
        
        
          P
        
        X
        T
      
    
    
  
 or not, i.e. 
  
    
      
        
          P
        
        X
        H
        ≠
        
          P
        
        X
        T
      
    
    
  
, where 
  
    
      
        H
        ,
        T
      
    
    
  
 denote the coin coming up heads or tails. 
The asymptotics of universal hypothesis testing were first discussed in Hoeffding's work on optimal tests for multinomial distributions. There have been many subsequent works on the topic in many directions. While Hoeffding's initial results were restricted to distributions with finite supports, later results developed solutions for continuous distributions using extensions of the Kullback-Leibler Divergence, or kernel methods.

## Related

- [[Error exponents in hypothesis testing]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]
- [[Bandwidth extension]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Universal_hypothesis_testing