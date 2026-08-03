---
title: "Information bottleneck method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Information_bottleneck_method"
wikipedia_categories: ["Cluster analysis algorithms", "Multivariate statistics"]
related: ["[[Cluster-weighted modeling]]", "[[Automatic clustering algorithms]]", "[[BIRCH]]", "[[Canopy clustering algorithm]]", "[[Cobweb (clustering)]]", "[[Constrained clustering]]", "[[Data stream clustering]]", "[[DBSCAN]]", "[[FLAME clustering]]", "[[Fuzzy clustering]]"]
---

# Information bottleneck method

The information bottleneck method is a technique in information theory introduced by Naftali Tishby, Fernando C. Pereira, and William Bialek. It is designed for finding the best tradeoff between accuracy and complexity (compression) when summarizing (e.g. clustering) a random variable X, given a joint probability distribution p(X,Y) between X and an observed relevant variable Y - and self-described as providing "a surprisingly rich framework for discussing a variety of problems in signal processing and learning".
Applications include distributional clustering and dimension reduction, and more recently it has been suggested as a theoretical foundation for deep learning. It generalized the classical notion of minimal sufficient statistics from parametric statistics to arbitrary distributions, not necessarily of exponential form. It does so by relaxing the sufficiency condition to capture some fraction of the mutual information with the relevant variable Y.
The information bottleneck can also be viewed as a rate distortion problem, with a distortion function that measures how well Y is predicted from a compressed representation T compared to its direct prediction from X. This interpretation provides a general iterative algorithm for solving the information bottleneck trade-off and calculating the information curve from the distribution p(X,Y).
Let the compressed representation be given by random variable 
  
    
      
        T
      
    
    
  
. The algorithm minimizes the following functional with respect to conditional distribution 
  
    
      
        p
        t
        
          |
        
        x
      
    
    
  
:

  
    
      
        
          inf
          
            p
            t
            
              |
            
            x
          
        
        
        
        
          
          
        
        I
        X
        ;
        T
        −
        β
        I
        T
        ;
        Y
        
          
          
        
        ,
      
    
    
  

where 
  
    
      
        I
        X
        ;
        T
      
    
    
  
 and 
  
    
      
        I
        T
        ;
        Y
      
    
    
  
 are the mutual information of 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        T
      
    
    
  
, and of 
  
    
      
        T
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
, respectively, and 
  
    
      
        β
      
    
    
  
 is a Lagrange multiplier.

## Related

- [[Cluster-weighted modeling]]
- [[Automatic clustering algorithms]]
- [[BIRCH]]
- [[Canopy clustering algorithm]]
- [[Cobweb (clustering)]]
- [[Constrained clustering]]
- [[Data stream clustering]]
- [[DBSCAN]]
- [[FLAME clustering]]
- [[Fuzzy clustering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Information_bottleneck_method