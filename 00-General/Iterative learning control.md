---
title: "Iterative learning control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Iterative_learning_control"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Iterative learning control

Iterative Learning Control (ILC) is an open-loop control approach of tracking control for systems that work in a repetitive mode. Examples of systems that operate in a repetitive manner include robot arm manipulators, chemical batch processes and reliability testing rigs. In each of these tasks the system is required to perform the same action over and over again with high precision. This action is represented by the objective of accurately tracking a chosen reference signal 
  
    
      
        r
        t
      
    
    
  
 on a finite time interval.
Repetition allows the system to sequentially improve tracking accuracy, in effect learning the required input needed to track the reference as closely as possible. The learning process uses information from previous repetitions to improve the control signal, ultimately enabling a suitable control action to be found iteratively. The internal model principle yields conditions under which perfect tracking can be achieved but the design of the control algorithm still leaves many decisions to be made to suit the application. A typical, simple control law is of the form:

  
    
      
        
          u
          
            p
            1
          
        
        
          u
          
            p
          
        
        K
        
          e
          
            p
          
        
      
    
    
  

where 
  
    
      
        
          u
          
            p
          
        
      
    
    
  
 is the input to the system during the pth repetition, 
  
    
      
        
          e
          
            p
          
        
      
    
    
  
 is the tracking error during the pth repetition and 
  
    
      
        K
      
    
    
  
 is a design parameter representing operations on 
  
    
      
        
          e
          
            p
          
        
      
    
    
  
. Achieving perfect tracking through iteration is represented by the mathematical requirement of convergence of the input signals as 
  
    
      
        p
      
    
    
  
 becomes large, whilst the rate of this convergence represents the desirable practical need for the learning process to be rapid. There is also the need to ensure good algorithm performance even in the presence of uncertainty about the details of process dynamics. The operation 
  
    
      
        K
      
    
    
  
 is crucial to achieving design objectives (i.e. trading off fast convergence and robust performance) and ranges from simple scalar gains to sophisticated optimization computations.
In many cases a low-pass filter is added to the input to improve performance. The control law then takes the form

  
    
      
        
          u
          
            p
            1
          
        
        Q
        
          u
          
            p
          
        
        K
        
          e
          
            p
          
        
      
    
    
  

where 
  
    
      
        Q
      
    
    
  
 is a low-pass filtering matrix. This removes high-frequency disturbances which may otherwise be amplified during the learning process.

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

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_learning_control