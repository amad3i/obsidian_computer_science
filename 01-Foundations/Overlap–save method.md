---
title: "Overlap–save method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Overlap–save_method"
wikipedia_categories: ["Fourier analysis", "Numerical analysis", "Signal processing", "Transforms"]
related: ["[[Overlap–add method]]", "[[Short-time Fourier transform]]", "[[Analytic signal]]", "[[Basis function]]", "[[Chirplet transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]", "[[Linear canonical transformation]]"]
---

# Overlap–save method

In signal processing, overlap–save is the traditional name for an efficient way to evaluate the discrete convolution between a very long signal 
  
    
      
        x
        n
      
    
    
  
 and a finite impulse response (FIR) filter 
  
    
      
        h
        n
      
    
    
  
:

where h[m] = 0 for m outside the region [1, M].
This article uses common abstract notations, such as 
  
    
      
        y
        t
        =
        x
        t
        ∗
        h
        t
        ,
      
    
    {\textstyle y(t)=x(t)*h(t),}
  
 or 
  
    
      
        y
        t
        =
        
          
            H
          
        
        x
        t
        }
        ,
      
    
    {\textstyle y(t)={\mathcal {H}}\{x(t)\},}
  
 in which it is understood that the functions should be thought of in their totality, rather than at specific instants 
  
    
      
        t
      
    
    {\textstyle t}
  
 (see Convolution#Notation).

The concept is to compute short segments of y[n] of an arbitrary length L, and concatenate the segments together.  That requires longer input segments that overlap the next input segment.  The overlapped data gets "saved" and used a second time.  First we describe that process with just conventional convolution for each output segment.  Then we describe how to replace that convolution with a more efficient method.
Consider a segment that begins at n = kL + M, for any integer k, and define:

  
    
      
        
          x
          
            k
          
        
        n
         
        ≜
        
          
            
              
                
                  x
                  n
                  k
                  L
                  ,
                
                
                  1
                  ≤
                  n
                  ≤
                  L
                  M
                  1
                
              
              
                
                  0
                  ,
                
                
                  
                    
                      otherwise
                    
                  
                  .
                
              
            
            
          
        
      
    
    
  

  
    
      
        
          y
          
            k
          
        
        n
         
        ≜
         
        
          x
          
            k
          
        
        n
        ∗
        h
        n
        =
        
          ∑
          
            m
            1
          
          
            M
          
        
        h
        m
        ⋅
        
          x
          
            k
          
        
        n
        m
        .
      
    
    
  

Then, for 
  
    
      
        k
        L
        M
        1
        ≤
        n
        ≤
        k
        L
        L
        M
      
    
    
  
, and equivalently 
  
    
      
        M
        1
        ≤
        n
        k
        L
        ≤
        L
        M
      
    
    
  
, we can write:

  
    
      
        y
        n
        =
        
          ∑
          
            m
            1
          
          
            M
          
        
        h
        m
        ⋅
        
          x
          
            k
          
        
        n
        k
        L
        m
         
         
        ≜
         
         
        
          y
          
            k
          
        
        n
        k
        L
        .
      
    
    
  

With the substitution 
  
    
      
        j
        n
        k
        L
      
    
    
  
, the task is reduced to computing 
  
    
      
        
          y
          
            k
          
        
        j
      
    
    
  
 for 
  
    
      
        M
        1
        ≤
        j
        ≤
        L
        M
      
    
    
  
.  These steps are illustrated in the first 3 traces of Figure 1, except that the desired portion of the output (third trace) corresponds to 1  ≤  j   ≤  L.
If we periodically extend xk[n] with period N  ≥  L + M − 1, according to:

  
    
      
        
          x
          
            k
            ,
            N
          
        
        n
         
        ≜
         
        
          ∑
          
            ℓ
            −
            ∞
          
          
            ∞
          
        
        
          x
          
            k
          
        
        n
        ℓ
        N
        ,
      
    
    
  

the convolutions  
  
    
      
        
          x
          
            k
            ,
            N
          
        
        ∗
        h
        
      
    
    
  
  and  
  
    
      
        
          x
          
            k
          
        
        h
        
      
    
    
  
  are equivalent in the region 
  
    
      
        M
        1
        ≤
        n
        ≤
        L
        M
      
    
    
  
. It is therefore sufficient to compute the N-point circular (or cyclic) convolution of 
  
    
      
        
          x
          
            k
          
        
        n
        
      
    
    
  
 with 
  
    
      
        h
        n
        
      
    
    
  
  in the region [1, N]. The subregion [M + 1, L + M] is appended to the output stream, and the other values are discarded. The advantage is that the circular convolution can be computed more efficiently than linear convolution, according to the circular convolution theorem:

where:

DFTN and IDFTN refer to the Discrete Fourier transform and its inverse, evaluated over N discrete points, and
L is customarily chosen such that N = L+M-1 is an integer power-of-2, and the transforms are implemented with the FFT algorithm, for efficiency.
The leading and trailing edge-effects of circular convolution are overlapped and added, and subsequently discarded.

## Related

- [[Overlap–add method]]
- [[Short-time Fourier transform]]
- [[Analytic signal]]
- [[Basis function]]
- [[Chirplet transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]
- [[Linear canonical transformation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Overlap–save_method