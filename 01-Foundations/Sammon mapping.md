---
title: "Sammon mapping"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sammon_mapping"
wikipedia_categories: ["Dimension reduction", "Functions and mappings", "Machine learning algorithms", "Statistics stubs"]
related: ["[[Canonical correspondence analysis]]", "[[Generalized multidimensional scaling]]", "[[Kernel principal component analysis]]", "[[Local tangent space alignment]]", "[[Multidimensional analysis]]", "[[Self-organizing map]]", "[[Semantic mapping (statistics)]]", "[[Sparse PCA]]", "[[Tucker decomposition]]", "[[3D projection]]"]
---

# Sammon mapping

Sammon mapping or Sammon projection is an algorithm that maps a high-dimensional space to a space of lower dimensionality (see multidimensional scaling) by trying to preserve the structure of inter-point distances in high-dimensional space in the lower-dimension projection.
It is particularly suited for use in exploratory data analysis.
The method was proposed by John W. Sammon in 1969. 
It is considered a non-linear approach as the mapping cannot be represented as a linear combination of the original variables as possible in techniques such as principal component analysis, which also makes it more difficult to use for classification applications.
Denote the distance between ith and jth objects in the original space by 
  
    
      
        
          
            d
            
              i
              j
            
            
            
          
        
      
    
    
  
, and the distance between their projections by 
  
    
      
        
          
            d
            
              i
              j
            
            

            
          
        
      
    
    
  
. 
Sammon's mapping aims to minimize the following error function, which is often referred to as Sammon's stress or Sammon's error:

  
    
      
        E
        
          
            1
            
              
                ∑
                
                  i
                  j
                
              
              
                d
                
                  i
                  j
                
                
                
              
            
          
        
        
          ∑
          
            i
            j
          
        
        
          
            
              
                d
                
                  i
                  j
                
                
                
              
              
                d
                
                  i
                  j
                
              
              
                
                  2
                
              
            
            
              d
              
                i
                j
              
              
              
            
          
        
        .
      
    
    
  

The minimization can be performed either by gradient descent, as proposed initially, or by other means, usually involving iterative methods. 
The number of iterations needs to be experimentally determined and convergent solutions are not always guaranteed. 
Many implementations prefer to use the first Principal Components as a starting configuration.
The Sammon mapping has been one of the most successful nonlinear metric multidimensional scaling methods since its advent in 1969, but effort has been focused on algorithm improvement rather than on the form of the stress function. 
The performance of the Sammon mapping has been improved by extending its stress function using left Bregman divergence 
 and right Bregman divergence.

## Related

- [[Canonical correspondence analysis]]
- [[Generalized multidimensional scaling]]
- [[Kernel principal component analysis]]
- [[Local tangent space alignment]]
- [[Multidimensional analysis]]
- [[Self-organizing map]]
- [[Semantic mapping (statistics)]]
- [[Sparse PCA]]
- [[Tucker decomposition]]
- [[3D projection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sammon_mapping