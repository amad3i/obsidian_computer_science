---
title: "Sufficient dimension reduction"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Sufficient_dimension_reduction"
wikipedia_categories: ["Dimension reduction"]
related: ["[[Canonical correspondence analysis]]", "[[Correspondence analysis]]", "[[Detrended correspondence analysis]]", "[[Feature selection]]", "[[Generalized canonical correlation]]", "[[Generalized multidimensional scaling]]", "[[Independent component analysis]]", "[[Kernel principal component analysis]]", "[[Local tangent space alignment]]", "[[Locality-sensitive hashing]]"]
---

# Sufficient dimension reduction

In statistics, sufficient dimension reduction (SDR) is a paradigm for analyzing data that combines the ideas of dimension reduction with the concept of sufficiency.
Dimension reduction has long been a primary goal of regression analysis. Given a response variable y and a p-dimensional predictor vector 
  
    
      
        
          
            x
          
        
      
    
    
  
, regression analysis aims to study the distribution of 
  
    
      
        y
        ∣
        
          
            x
          
        
      
    
    
  
, the conditional distribution of 
  
    
      
        y
      
    
    
  
 given 
  
    
      
        
          
            x
          
        
      
    
    
  
. A dimension reduction is a function 
  
    
      
        R
        
          
            x
          
        
      
    
    
  
 that maps 
  
    
      
        
          
            x
          
        
      
    
    
  
 to a subset of 
  
    
      
        
          
            R
          
          
            k
          
        
      
    
    
  
, k < p, thereby reducing the dimension of 
  
    
      
        
          
            x
          
        
      
    
    
  
. For example, 
  
    
      
        R
        
          
            x
          
        
      
    
    
  
 may be one or more linear combinations of 
  
    
      
        
          
            x
          
        
      
    
    
  
.
A dimension reduction 
  
    
      
        R
        
          
            x
          
        
      
    
    
  
 is said to be sufficient if the distribution of 
  
    
      
        y
        ∣
        R
        
          
            x
          
        
      
    
    
  
 is the same as that of 
  
    
      
        y
        ∣
        
          
            x
          
        
      
    
    
  
. In other words, no information about the regression is lost in reducing the dimension of 
  
    
      
        
          
            x
          
        
      
    
    
  
 if the reduction is sufficient.

## Related

- [[Canonical correspondence analysis]]
- [[Correspondence analysis]]
- [[Detrended correspondence analysis]]
- [[Feature selection]]
- [[Generalized canonical correlation]]
- [[Generalized multidimensional scaling]]
- [[Independent component analysis]]
- [[Kernel principal component analysis]]
- [[Local tangent space alignment]]
- [[Locality-sensitive hashing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sufficient_dimension_reduction