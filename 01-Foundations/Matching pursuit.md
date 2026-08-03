---
title: "Matching pursuit"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Matching_pursuit"
wikipedia_categories: ["Multivariate statistics", "Signal processing"]
related: ["[[Least-squares spectral analysis]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]"]
---

# Matching pursuit

Matching pursuit (MP) is a sparse approximation algorithm which finds the "best matching" projections of multidimensional data onto the span of an over-complete (i.e., redundant) dictionary 
  
    
      
        D
      
    
    
  
. The basic idea is to approximately represent a signal 
  
    
      
        f
      
    
    
  
 from Hilbert space 
  
    
      
        H
      
    
    
  
 as a weighted sum of finitely many functions 
  
    
      
        
          g
          
            
              γ
              
                n
              
            
          
        
      
    
    
  
 (called atoms) taken from 
  
    
      
        D
      
    
    
  
. An approximation with 
  
    
      
        N
      
    
    
  
 atoms has the form

  
    
      
        f
        t
        ≈
        
          
            
              
                f
                ^
              
            
          
          
            N
          
        
        t
        :=
        
          ∑
          
            n
            1
          
          
            N
          
        
        
          a
          
            n
          
        
        
          g
          
            
              γ
              
                n
              
            
          
        
        t
      
    
    
  

where 
  
    
      
        
          g
          
            
              γ
              
                n
              
            
          
        
      
    
    
  
 is the 
  
    
      
        
          γ
          
            n
          
        
      
    
    
  
th column of the matrix 
  
    
      
        D
      
    
    
  
 and 
  
    
      
        
          a
          
            n
          
        
      
    
    
  
 is the scalar weighting factor (amplitude) for the atom 
  
    
      
        
          g
          
            
              γ
              
                n
              
            
          
        
      
    
    
  
. Normally, not every atom in 
  
    
      
        D
      
    
    
  
 will be used in this sum. Instead, matching pursuit chooses the atoms one at a time in order to maximally (greedily) reduce the approximation error. This is achieved by finding the atom that has the highest inner product with the signal (assuming the atoms are normalized), subtracting from the signal an approximation that uses only that one atom, and repeating the process until the signal is satisfactorily decomposed, i.e., the norm of the residual is small,
where the residual after calculating 
  
    
      
        
          γ
          
            N
          
        
      
    
    
  
 and 
  
    
      
        
          a
          
            N
          
        
      
    
    
  
 is denoted by

  
    
      
        
          R
          
            N
            1
          
        
        f
        
          
            
              
                f
                ^
              
            
          
          
            N
          
        
      
    
    
  
.
If 
  
    
      
        
          R
          
            n
          
        
      
    
    
  
 converges quickly to zero, then only a few atoms are needed to get a good approximation to 
  
    
      
        f
      
    
    
  
. Such sparse representations are desirable for signal coding and compression. More precisely, the sparsity problem that matching pursuit is intended to approximately solve is

  
    
      
        
          min
          
            x
          
        
        ‖
        f
        D
        x
        
          ‖
          
            2
          
          
            2
          
        
         
        
           subject to 
        
         
        ‖
        x
        
          ‖
          
            0
          
        
        ≤
        N
        ,
      
    
    
  

where 
  
    
      
        ‖
        x
        
          ‖
          
            0
          
        
      
    
    
  
 is the 
  
    
      
        
          L
          
            0
          
        
      
    
    
  
 pseudo-norm (i.e. the number of nonzero elements of 
  
    
      
        x
      
    
    
  
). In the previous notation, the nonzero entries of 
  
    
      
        x
      
    
    
  
 are 
  
    
      
        
          x
          
            
              γ
              
                n
              
            
          
        
        
          a
          
            n
          
        
      
    
    
  
. Solving the sparsity problem exactly is NP-hard, which is why approximation methods like MP are used.
For comparison, consider the Fourier transform representation of a signal - this can be described using the terms given above, where the dictionary is built from sinusoidal basis functions (the smallest possible complete dictionary). The main disadvantage of Fourier analysis in signal processing is that it extracts only the global features of the signals and does not adapt to the analysed signals 
  
    
      
        f
      
    
    
  
.  
By taking an extremely redundant dictionary, we can look in it for atoms (functions) that best match a signal 
  
    
      
        f
      
    
    
  
.

## Related

- [[Least-squares spectral analysis]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Matching_pursuit