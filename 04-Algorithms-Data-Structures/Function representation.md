---
title: "Function representation"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Function_representation"
wikipedia_categories: ["3D computer graphics", "Computer graphics", "Geometric algorithms"]
related: ["[[3D computer graphics]]", "[[Bounding volume]]", "[[Fiducial marker]]", "[[Geometric primitive]]", "[[Hierarchical RBF]]", "[[Joint constraints]]", "[[Kinematic chain]]", "[[Mesh generation]]", "[[Per-pixel lighting]]", "[[Progressive-iterative approximation method]]"]
---

# Function representation

Function Representation (FRep
 or F-Rep) is used in solid modeling, volume modeling and computer graphics. FRep was introduced in "Function representation in geometric modeling: concepts, implementation and applications"  as a uniform representation of multidimensional geometric objects (shapes). An object as a point set in multidimensional space is defined by a single continuous real-valued function 
  
    
      
        f
        X
      
    
    
  
 of point coordinates 
  
    
      
        X
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
      
    
    
  
 which is evaluated at the given point by a procedure traversing a tree structure with primitives in the leaves and operations in the nodes of the tree. The points with 
  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
        ≥
        0
      
    
    
  
 belong to the object, and the points with 
  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
        <
        0
      
    
    
  
 are outside of the object. The point set with 
  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
        =
        0
      
    
    
  
 is called an isosurface.

## Related

- [[3D computer graphics]]
- [[Bounding volume]]
- [[Fiducial marker]]
- [[Geometric primitive]]
- [[Hierarchical RBF]]
- [[Joint constraints]]
- [[Kinematic chain]]
- [[Mesh generation]]
- [[Per-pixel lighting]]
- [[Progressive-iterative approximation method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Function_representation