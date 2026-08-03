---
title: "Smith predictor"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Smith_predictor"
wikipedia_categories: ["Control theory", "Systems theory stubs"]
related: ["[[Compensator (control theory)]]", "[[Cross Gramian]]", "[[Meta-system]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Activity cycle diagram]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]"]
---

# Smith predictor

The Smith predictor (invented by O. J. M. Smith in 1957) is a type of predictive controller designed to control systems with a significant feedback time delay. The idea can be illustrated as follows.
Suppose the plant consists of 
  
    
      
        G
        z
      
    
    
  
 followed by a pure time delay 
  
    
      
        
          z
          
            k
          
        
      
    
    
  
. 
  
    
      
        z
      
    
    
  
 refers to the Z-transform of the transfer function relating the inputs and outputs of the plant 
  
    
      
        G
      
    
    
  
.
As a first step, suppose we only consider 
  
    
      
        G
        z
      
    
    
  
 (the plant without a delay) and design a controller 
  
    
      
        C
        z
      
    
    
  
 with a closed-loop transfer function 
  
    
      
        H
        z
        =
        
          
            
              C
              z
              G
              z
            
            
              1
              C
              z
              G
              z
            
          
        
      
    
    
  
 that we consider satisfactory.
Next, our objective is to design a controller 
  
    
      
        
          
            
              C
              ¯
            
          
        
        z
      
    
    
  
 for the plant 
  
    
      
        G
        z
        
          z
          
            k
          
        
      
    
    
  
 so that the closed loop transfer function 
  
    
      
        
          
            
              H
              ¯
            
          
        
        z
      
    
    
  
 equals 
  
    
      
        H
        z
        
          z
          
            k
          
        
      
    
    
  
.
Solving 
  
    
      
        
          
            
              
                
                  
                    C
                    ¯
                  
                
              
              G
              
                z
                
                  k
                
              
            
            
              1
              
                
                  
                    C
                    ¯
                  
                
              
              G
              
                z
                
                  k
                
              
            
          
        
        
          z
          
            k
          
        
        
          
            
              C
              G
            
            
              1
              C
              G
            
          
        
      
    
    
  
,
we obtain

  
    
      
        
          
            
              C
              ¯
            
          
        
        
          
            C
            
              1
              C
              G
              1
              
                z
                
                  k
                
              
            
          
        
      
    
    
  
. The controller is implemented as shown in the following figure, where 
  
    
      
        G
        z
      
    
    
  
 has been changed to 
  
    
      
        
          
            
              G
              ^
            
          
        
        z
      
    
    
  
 to indicate that it is a model used by the controller.

Note that there are two feedback loops.  The outer control loop feeds the output back to the input, as usual. However, this loop alone would not provide satisfactory control, because of the delay; this loop is feeding back outdated information.  Intuitively, for the k sample intervals during which no fresh information is available, the system is controlled by the inner loop which contains a predictor of what the (unobservable) output of the plant G currently is.
To check that this works, a re-arrangement can be made as follows:

Here we can see that if the model used in the controller, 
  
    
      
        
          
            
              G
              ^
            
          
        
        z
        
          z
          
            k
          
        
      
    
    
  
,  matches the plant 
  
    
      
        G
        z
        
          z
          
            k
          
        
      
    
    
  
 perfectly, then the outer and middle feedback loops cancel each other, and the controller generates the "correct" control action. In reality, however, it is impossible for the model to perfectly match the plant.

## Related

- [[Compensator (control theory)]]
- [[Cross Gramian]]
- [[Meta-system]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Activity cycle diagram]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smith_predictor