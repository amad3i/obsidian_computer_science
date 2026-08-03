---
title: "Patlak plot"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Patlak_plot"
wikipedia_categories: ["Mathematical modeling", "Pharmacokinetics", "Plots (graphics)", "Systems theory"]
related: ["[[Logan plot]]", "[[Linear system]]", "[[Modelling biological systems]]", "[[Multi-compartment model]]", "[[PottersWheel]]", "[[Active and passive transformation]]", "[[Activity cycle diagram]]", "[[Allopoiesis]]", "[[AMPL]]", "[[Analytica (software)]]"]
---

# Patlak plot

A Patlak plot (sometimes called Gjedde–Patlak plot, Patlak–Rutland plot, or Patlak analysis) is a graphical analysis technique based on the compartment model that uses linear regression to identify and analyze pharmacokinetics of tracers involving irreversible uptake, such as in the case of deoxyglucose. It is used for the evaluation of nuclear medicine imaging data after the injection of a radioopaque or radioactive tracer.
The method is model-independent because it does not depend on any specific compartmental model configuration for the tracer, and the minimal assumption is that the behavior of the tracer can be approximated by two compartments – a "central" (or reversible) compartment that is in rapid equilibrium with plasma, and a "peripheral" (or irreversible) compartment, where tracer enters without ever leaving during the time of the measurements.  The amount of tracer in the region of interest is accumulating according to the equation:

  
    
      
        R
        t
        =
        K
        
          ∫
          
            0
          
          
            t
          
        
        
          C
          
            p
          
        
        τ
        
        d
        τ
        
          V
          
            0
          
        
        
          C
          
            p
          
        
        t
      
    
    
  

where 
  
    
      
        t
      
    
    
  
 represents time after tracer injection, 
  
    
      
        R
        t
      
    
    
  
 is the amount of tracer in region of interest, 
  
    
      
        
          C
          
            p
          
        
        t
      
    
    
  
 is the concentration of tracer in plasma or blood, 
  
    
      
        K
      
    
    
  
 is the clearance determining the rate of entry into the peripheral (irreversible) compartment, and 
  
    
      
        
          V
          
            0
          
        
      
    
    
  
 is the distribution volume of the tracer in the central compartment. The first term of the right-hand side represents tracer in the peripheral compartment, and the second term tracer in the central compartment.
By dividing both sides by 
  
    
      
        
          C
          
            p
          
        
        t
      
    
    
  
, one obtains:

  
    
      
        
          
            
              R
              t
            
            
              
                C
                
                  p
                
              
              t
            
          
        
        K
        
          
            
              
                ∫
                
                  0
                
                
                  t
                
              
              
                C
                
                  p
                
              
              τ
              
              d
              τ
            
            
              
                C
                
                  p
                
              
              t
            
          
        
        
          V
          
            0
          
        
      
    
    
  

The unknown constants 
  
    
      
        K
      
    
    
  
 and 
  
    
      
        
          V
          
            0
          
        
      
    
    
  
 can be obtained by linear regression from a graph of 
  
    
      
        
          
            
              R
              t
            
            
              
                C
                
                  p
                
              
              t
            
          
        
      
    
    
  
 against 
  
    
      
        
          ∫
          
            0
          
          
            t
          
        
        
          C
          
            p
          
        
        τ
        
        d
        τ
        
          /
        
        
          C
          
            p
          
        
        t
      
    
    
  
.

## Related

- [[Logan plot]]
- [[Linear system]]
- [[Modelling biological systems]]
- [[Multi-compartment model]]
- [[PottersWheel]]
- [[Active and passive transformation]]
- [[Activity cycle diagram]]
- [[Allopoiesis]]
- [[AMPL]]
- [[Analytica (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Patlak_plot