---
title: "Catastrophic cancellation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Catastrophic_cancellation"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Catastrophic cancellation

In numerical analysis, catastrophic cancellation is the phenomenon that subtracting good approximations to two nearby numbers may yield a very bad approximation to the difference of the original numbers.
For example, if there are two studs, one 
  
    
      
        
          L
          
            1
          
        
        253.51
        
        
          cm
        
      
    
    
  
 long and the other 
  
    
      
        
          L
          
            2
          
        
        252.49
        
        
          cm
        
      
    
    
  
 long, and they are measured with a ruler that is good only to the centimeter, then the approximations could come out to be 
  
    
      
        
          
            
              
                L
                ~
              
            
          
          
            1
          
        
        254
        
        
          cm
        
      
    
    
  
 and 
  
    
      
        
          
            
              
                L
                ~
              
            
          
          
            2
          
        
        252
        
        
          cm
        
      
    
    
  
.
These may be good approximations, in relative error, to the true lengths: the approximations are in error by less than 0.2% of the true lengths, 
  
    
      
        
          |
        
        
          L
          
            1
          
        
        
          
            
              
                L
                ~
              
            
          
          
            1
          
        
        
          |
        
        
          /
        
        
          |
        
        
          L
          
            1
          
        
        
          |
        
        0.2
        %
      
    
    
  
.
However, if the approximate lengths are subtracted, the difference will be 
  
    
      
        
          
            
              
                L
                ~
              
            
          
          
            1
          
        
        
          
            
              
                L
                ~
              
            
          
          
            2
          
        
        254
        
        
          cm
        
        252
        
        
          cm
        
        2
        
        
          cm
        
      
    
    
  
, even though the true difference between the lengths is 
  
    
      
        
          L
          
            1
          
        
        
          L
          
            2
          
        
        253.51
        
        
          cm
        
        252.49
        
        
          cm
        
        1.02
        
        
          cm
        
      
    
    
  
.
The difference of the approximations, 
  
    
      
        2
        
        
          cm
        
      
    
    
  
, is in error by almost 100% of the magnitude of the difference of the 
true values, 
  
    
      
        1.02
        
        
          cm
        
      
    
    
  
.
Catastrophic cancellation is not affected by how large the inputs are—it applies just as much to large and small inputs.
It depends only on how large the difference is, and on the error of the inputs.
Exactly the same error would arise by subtracting 
  
    
      
        52
        
        
          cm
        
      
    
    
  
 from 
  
    
      
        54
        
        
          cm
        
      
    
    
  
 as approximations to 
  
    
      
        52.49
        
        
          cm
        
      
    
    
  
 and 
  
    
      
        53.51
        
        
          cm
        
      
    
    
  
, or by subtracting 
  
    
      
        2.00052
        
        
          km
        
      
    
    
  
 from 
  
    
      
        2.00054
        
        
          km
        
      
    
    
  
 as approximations to 
  
    
      
        2.0005249
        
        
          km
        
      
    
    
  
 and 
  
    
      
        2.0005351
        
        
          km
        
      
    
    
  
.
Catastrophic cancellation may happen even if the difference is computed exactly, as in the example above—it is not a property of any particular kind of arithmetic like floating-point arithmetic; rather, it is inherent to subtraction, when the inputs are approximations themselves.  Indeed, in floating-point arithmetic, when the inputs are close enough, the floating-point difference is computed exactly, by the Sterbenz lemma—there is no rounding error introduced by the floating-point subtraction operation.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Catastrophic_cancellation