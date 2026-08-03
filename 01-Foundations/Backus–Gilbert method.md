---
title: "Backus–Gilbert method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Backus–Gilbert_method"
wikipedia_categories: ["Inverse problems", "Linear algebra"]
related: ["[[Regularized least squares]]", "[[Ridge regression]]", "[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]"]
---

# Backus–Gilbert method

In mathematics, the Backus–Gilbert method, also known as the optimally localized average (OLA) method is named for its discoverers, geophysicists George E. Backus and James Freeman Gilbert. It is a regularization method for obtaining meaningful solutions to ill-posed inverse problems.  Where other regularization methods, such as the frequently used Tikhonov regularization method, seek to impose smoothness constraints on the solution, Backus–Gilbert instead seeks to impose stability constraints, so that the solution would vary as little as possible if the input data were resampled multiple times.  In practice, and to the extent that is justified by the data, smoothness results from this.
Given a data array X, the basic Backus-Gilbert inverse is:

  
    
      
        
          
            H
          
          
            θ
          
        
        
          
            
              
                
                  C
                
                
                  1
                
              
              
                
                  G
                
                
                  θ
                
              
            
            
              
                
                  G
                
                
                  θ
                
                
                  T
                
              
              
                
                  C
                
                
                  1
                
              
              
                
                  G
                
                
                  θ
                
              
            
          
        
      
    
    
  

where C is the covariance matrix of the data, and Gθ is an a priori constraint representing the source θ for which a solution is sought. Regularization is implemented by "whitening" the covariance matrix:

  
    
      
        
          
            C
          
          ′
        
        
          C
        
        λ
        
          I
        
      
    
    
  

with C′ replacing C in the equation for Hθ. Then,

  
    
      
        
          
            H
          
          
            θ
          
          
            T
          
        
        
          X
        
      
    
    
  

is an estimate of the activity of the source θ.

## Related

- [[Regularized least squares]]
- [[Ridge regression]]
- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Backus–Gilbert_method