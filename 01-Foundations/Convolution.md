---
title: "Convolution"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Convolution"
wikipedia_categories: ["Bilinear maps", "Feature detection (computer vision)", "Fourier analysis", "Functional analysis", "Image processing"]
related: ["[[Negacyclic convolution]]", "[[Chirplet transform]]", "[[Circle Hough Transform]]", "[[Circular convolution]]", "[[Co-occurrence matrix]]", "[[Image histogram]]", "[[Kernel (image processing)]]", "[[List of Fourier-related transforms]]", "[[Orthonormal basis]]", "[[Robinson compass mask]]"]
---

# Convolution

In mathematics (in particular, functional analysis), convolution is a mathematical operation on two functions 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
 that produces a third function 
  
    
      
        f
        g
      
    
    
  
, as the integral of the product of the two functions after one is reflected about the y-axis and shifted. The term convolution refers to both the resulting function and to the process of computing it. The integral is evaluated for all values of shift, producing the convolution function. The choice of which function is reflected and shifted before the integral does not change the integral result (see commutativity). Graphically, it expresses how the 'shape' of one function is modified by the other.
Some features of convolution are similar to cross-correlation: for real-valued functions, of a continuous or discrete variable, convolution 
  
    
      
        f
        g
      
    
    
  
 differs from cross-correlation 
  
    
      
        f
        ⋆
        g
      
    
    
  
 only in that either 
  
    
      
        f
        x
      
    
    
  
 or 
  
    
      
        g
        x
      
    
    
  
 is reflected about the y-axis in convolution; thus it is a cross-correlation of 
  
    
      
        g
        −
        x
      
    
    
  
 and 
  
    
      
        f
        x
      
    
    
  
, or 
  
    
      
        f
        −
        x
      
    
    
  
 and 
  
    
      
        g
        x
      
    
    
  
. For complex-valued functions, the cross-correlation operator is the adjoint of the convolution operator.
Convolution has applications that include probability, statistics, acoustics, spectroscopy, signal processing and image processing, computer vision and human vision, geophysics, engineering, physics, and differential equations.
The convolution can be defined for functions on Euclidean space and other groups (as algebraic structures). For example, periodic functions, such as the discrete-time Fourier transform, can be defined on a circle and convolved by periodic convolution. (See row 18 at DTFT § Properties.) A discrete convolution can be defined for functions on the set of integers.
Generalizations of convolution have applications in the field of numerical analysis and numerical linear algebra, and in the design and implementation of finite impulse response filters in signal processing.
Computing the inverse of the convolution operation is known as deconvolution.

## Related

- [[Negacyclic convolution]]
- [[Chirplet transform]]
- [[Circle Hough Transform]]
- [[Circular convolution]]
- [[Co-occurrence matrix]]
- [[Image histogram]]
- [[Kernel (image processing)]]
- [[List of Fourier-related transforms]]
- [[Orthonormal basis]]
- [[Robinson compass mask]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Convolution