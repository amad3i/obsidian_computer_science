---
title: "Implicit surface"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Implicit_surface"
wikipedia_categories: ["Computer-aided design", "Geometry processing", "Implicit surface modeling", "Mesh generation", "Surfaces"]
related: ["[[Class A surface]]", "[[Digital modeling and fabrication]]", "[[Freeform surface modelling]]", "[[Isosurface]]", "[[Marching cubes]]", "[[Mesh generation]]", "[[PDE surface]]", "[[Polygon mesh]]", "[[Surface triangulation]]", "[[Tessellation (computer graphics)]]"]
---

# Implicit surface

In mathematics, an implicit surface is a surface in Euclidean space defined by an equation 

  
    
      
        F
        x
        ,
        y
        ,
        z
        =
        0.
      
    
    
  

An implicit surface is the set of zeros of a function of three variables. Implicit means that the equation is not solved for x or y or z.
The graph of a function is usually described by an equation 
  
    
      
        z
        f
        x
        ,
        y
      
    
    
  
 and is called an explicit representation. The third essential description of a surface is the parametric one: 

  
    
      
        x
        s
        ,
        t
        ,
        y
        s
        ,
        t
        ,
        z
        s
        ,
        t
        )
      
    
    
  
, where the x-, y- and z-coordinates of surface points are represented by three functions 
  
    
      
        x
        s
        ,
        t
        
        ,
        y
        s
        ,
        t
        
        ,
        z
        s
        ,
        t
      
    
    
  
 depending on common parameters 
  
    
      
        s
        ,
        t
      
    
    
  
. Generally the change of representations is simple only when the explicit representation 
  
    
      
        z
        f
        x
        ,
        y
      
    
    
  
 is given: 
  
    
      
        z
        f
        x
        ,
        y
        =
        0
      
    
    
  
 (implicit), 
  
    
      
        s
        ,
        t
        ,
        f
        s
        ,
        t
        )
      
    
    
  
 (parametric).
Examples:

The plane 
  
    
      
        x
        2
        y
        3
        z
        1
        0.
      
    
    
  

The sphere 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        
          z
          
            2
          
        
        4
        0.
      
    
    
  

The torus 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        
          z
          
            2
          
        
        
          R
          
            2
          
        
        
          a
          
            2
          
        
        
          
            2
          
        
        4
        
          R
          
            2
          
        
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        =
        0.
      
    
    
  

A surface of genus 2: 
  
    
      
        2
        y
        
          y
          
            2
          
        
        3
        
          x
          
            2
          
        
        (
        1
        
          z
          
            2
          
        
        +
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        
          
            2
          
        
        (
        9
        
          z
          
            2
          
        
        1
        (
        1
        
          z
          
            2
          
        
        =
        0
      
    
    
  
 (see diagram).
The surface of revolution 
  
    
      
        
          x
          
            2
          
        
        
          y
          
            2
          
        
        (
         
        z
        3.2
        
          
            2
          
        
        0.02
        0
      
    
    
  
 (see diagram wineglass).
For a plane, a sphere, and a torus there exist simple parametric representations. This is not true for the fourth example.
The implicit function theorem describes conditions under which an equation 
  
    
      
        F
        x
        ,
        y
        ,
        z
        =
        0
      
    
    
  
 can be solved (at least implicitly) for x, y or z. But in general the solution may not be made explicit. This theorem is the key to the computation of essential geometric features of a surface: tangent planes, surface normals, curvatures (see below). But they have an essential drawback: their visualization is difficult.
If 
  
    
      
        F
        x
        ,
        y
        ,
        z
      
    
    
  
 is polynomial in x, y and z, the surface is called algebraic. Example 5 is non-algebraic.
Despite difficulty of visualization, implicit surfaces provide relatively simple techniques to generate theoretically (e.g. Steiner surface) and practically (see below) interesting surfaces.

## Related

- [[Class A surface]]
- [[Digital modeling and fabrication]]
- [[Freeform surface modelling]]
- [[Isosurface]]
- [[Marching cubes]]
- [[Mesh generation]]
- [[PDE surface]]
- [[Polygon mesh]]
- [[Surface triangulation]]
- [[Tessellation (computer graphics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implicit_surface