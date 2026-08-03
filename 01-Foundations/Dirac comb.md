---
title: "Dirac comb"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dirac_comb"
wikipedia_categories: ["Directional statistics", "Generalized functions", "Signal processing", "Special functions"]
related: ["[[Abramowitz and Stegun]]", "[[Ackermann function]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]"]
---

# Dirac comb

In mathematics, a Dirac comb (also known as sha function, impulse train or sampling function) is a periodic generalized function with the formula

  
    
      
        
          
            Ш
          
          
            T
          
        
         
        t
        :=
        
          ∑
          
            k
            −
            ∞
          
          
            ∞
          
        
        δ
        t
        k
        T
      
    
    
  

for some given period ⁠
  
    
      
        T
      
    
    
  
⁠. Here ⁠
  
    
      
        t
      
    
    
  
⁠ is a real variable and the sum extends over all integers ⁠
  
    
      
        k
      
    
    
  
⁠. The Dirac delta function 
  
    
      
        δ
      
    
    
  
 and the Dirac comb are tempered distributions. The graph of the function resembles a comb (with the 
  
    
      
        δ
      
    
    
  
s as the comb's 'teeth'), hence its name and the use of the comb-like Cyrillic letter sha (Ш) to denote the function.
The symbol ⁠
  
    
      
        
          Ш
        
        t
      
    
    
  
⁠, where the period ⁠
  
    
      
        T
      
    
    
  
⁠ is omitted, represents a Dirac comb of unit period:

  
    
      
        
          Ш
        
         
        t
        :=
        
          
            Ш
          
          
            1
          
        
         
        t
        =
        
          ∑
          
            k
            −
            ∞
          
          
            ∞
          
        
        δ
        t
        k
      
    
    
  

This implies

  
    
      
        
          
            Ш
          
          
            T
          
        
         
        t
        =
        
          
            1
            T
          
        
        
          Ш
        
        
        
          
            
              t
            
            
              /
            
            
              T
            
          
        
        .
      
    
    
  

Because the Dirac comb function is periodic, it can be represented as a Fourier series based on the Dirichlet kernel:

  
    
      
        
          
            Ш
          
          
            T
          
        
         
        t
        =
        
          
            1
            T
          
        
        
          ∑
          
            n
            −
            ∞
          
          
            ∞
          
        
        
          e
          
            i
            2
            π
            n
            
              t
            
            
              /
            
            
              T
            
          
        
        .
      
    
    
  

The Dirac comb function allows one to represent both continuous and discrete phenomena, such as sampling and aliasing, in a single framework of continuous Fourier analysis on tempered distributions, without any reference to Fourier series.  The Fourier transform of a Dirac comb is another Dirac comb. Owing to the convolution theorem on tempered distributions which turns out to be the Poisson summation formula, in signal processing, the Dirac comb allows modelling sampling by multiplication with it, but it also allows modelling periodization by convolution with it.

## Related

- [[Abramowitz and Stegun]]
- [[Ackermann function]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dirac_comb