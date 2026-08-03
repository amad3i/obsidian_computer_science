---
title: "Class kappa function"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Class_kappa_function"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Class kappa function

In control theory, it is often required to check if a nonautonomous system is stable or not. To cope with this it is necessary to use some special comparison functions. Class 
  
    
      
        
          
            K
          
        
      
    
    
  
 functions belong to this family:

Definition: a continuous function 
  
    
      
        α
        :
        0
        ,
        a
        →
        0
        ,
        ∞
      
    
    
  
 is said to belong to class 
  
    
      
        
          
            K
          
        
      
    
    
  
 if:

it is strictly increasing;
it is s.t. 
  
    
      
        α
        0
        =
        0
      
    
    
  
.
In fact, this is nothing but the definition of the norm except for the triangular inequality.

Definition: a continuous function 
  
    
      
        α
        :
        0
        ,
        a
        →
        0
        ,
        ∞
      
    
    
  
 is said to belong to class 
  
    
      
        
          
            
              K
            
          
          
            ∞
          
        
      
    
    
  
 if:

it belongs to class 
  
    
      
        
          
            K
          
        
      
    
    
  
;
it is s.t. 
  
    
      
        a
        ∞
      
    
    
  
;
it is s.t. 
  
    
      
        
          
            r
            →
            ∞
          
        
        α
        r
        =
        ∞
      
    
    
  
.
A nondecreasing positive definite function 
  
    
      
        β
      
    
    
  
 satisfying all conditions of class 
  
    
      
        
          
            K
          
        
      
    
    
  
  
    
      
        
          
            
              K
            
          
          
            ∞
          
        
      
    
    
  
) other than being strictly increasing can be upper and lower bounded by class 
  
    
      
        
          
            K
          
        
      
    
    
  
  
    
      
        
          
            
              K
            
          
          
            ∞
          
        
      
    
    
  
) functions as follows:

  
    
      
        β
        x
        
          
            x
            
              x
              1
            
          
        
        β
        x
        <
        β
        x
        
          
            
              
                x
                
                  x
                  1
                
              
            
            1
          
        
        β
        x
        
          
            
              2
              x
              1
            
            
              x
              1
            
          
        
        ,
        
        x
        ∈
        0
        ,
        a
        .
        
      
    
    
  

Thus, to proceed with the appropriate analysis, it suffices to bound the function of interest with continuous nonincreasing positive definite functions.
In other words, when a function belongs to the (
  
    
      
        
          
            
              K
            
          
          
            ∞
          
        
      
    
    
  
) it means that the function is radially unbounded.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Class_kappa_function