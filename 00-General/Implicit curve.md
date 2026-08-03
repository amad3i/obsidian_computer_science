---
title: "Implicit curve"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Implicit_curve"
wikipedia_categories: ["Computer-aided design", "Curves"]
related: ["[[Isophote]]", "[[2D geometric model]]", "[[3D Content Retrieval]]", "[[3D floor plan]]", "[[3D Systems]]", "[[AgcXML]]", "[[Algorithms-Aided Design]]", "[[Architectural animation]]", "[[Architectural geometry]]", "[[Architectural illustration]]"]
---

# Implicit curve

In mathematics, an implicit curve is a plane curve defined by an implicit equation relating two coordinate variables, commonly x and y. For example, the unit circle is defined by the implicit equation 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        1
      
    
    
  
. In general, every implicit curve is defined by an equation of the form

  
    
      
        F
        x
        ,
        y
        =
        0
      
    
    
  

for some function F of two variables. Hence an implicit curve can be considered as the set of zeros of a function of two variables. Implicit means that the equation is not expressed as a solution for either x in terms of y or vice versa.
If 
  
    
      
        F
        x
        ,
        y
      
    
    
  
 is a polynomial in two variables, the corresponding curve is called an algebraic curve, and specific methods are available for studying it.
Plane curves can be represented in Cartesian coordinates (x, y coordinates) by any of three methods, one of which is the implicit equation given above. The graph of a function is usually described by an equation 
  
    
      
        y
        f
        x
      
    
    
  
 in which the functional form is explicitly stated; this is called an explicit representation. The third essential description of a curve is the parametric one, where the x- and y-coordinates of curve points are represented by 
two functions x(t), y(t) both of whose functional forms are explicitly stated, and which are dependent on a common parameter 
  
    
      
        t
        .
      
    
    
  

Examples of implicit curves include:

a line: 
  
    
      
        x
        2
        y
        3
        0
        ,
      
    
    
  

a circle: 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        4
        0
        ,
      
    
    
  

the semicubical parabola: 
  
    
      
        
          x
          
            3
          
        
        
          y
          
            2
          
        
        0
        ,
      
    
    
  

Cassini ovals 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        
          
            2
          
        
        2
        
          c
          
            2
          
        
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        −
        
          a
          
            4
          
        
        
          c
          
            4
          
        
        =
        0
      
    
    
  
 (see diagram),

  
    
      
         
        x
        y
        −
         
        x
        y
        +
        1
        0
      
    
    
  
 (see diagram).
The first four examples are algebraic curves, but the last one is not algebraic. The first three examples possess simple parametric representations, which is not true for the fourth and fifth examples. The fifth example shows the possibly complicated geometric structure of an implicit curve.
The implicit function theorem describes conditions under which an equation 
  
    
      
        F
        x
        ,
        y
        =
        0
      
    
    
  
 can be solved implicitly for x and/or y – that is, under which one can validly write 
  
    
      
        x
        g
        y
      
    
    
  
 or 
  
    
      
        y
        f
        x
      
    
    
  
. This theorem is the key for the computation of essential geometric features of the curve: tangents, normals, and curvature. In practice implicit curves have an essential drawback: their visualization is difficult. But there are computer programs enabling one to display an implicit curve. Special properties of implicit curves make them essential tools in geometry and computer graphics.
An implicit curve with an equation 
  
    
      
        F
        x
        ,
        y
        =
        0
      
    
    
  
 can be considered as the level curve of level 0 of the surface 
  
    
      
        z
        F
        x
        ,
        y
      
    
    
  
 (see third diagram).

## Related

- [[Isophote]]
- [[2D geometric model]]
- [[3D Content Retrieval]]
- [[3D floor plan]]
- [[3D Systems]]
- [[AgcXML]]
- [[Algorithms-Aided Design]]
- [[Architectural animation]]
- [[Architectural geometry]]
- [[Architectural illustration]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implicit_curve