---
title: "Bentley–Ottmann algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bentley–Ottmann_algorithm"
wikipedia_categories: ["Computational geometry", "Geometric algorithms"]
related: ["[[Euclidean shortest path]]", "[[Multiple line segment intersection]]", "[[Progressive-iterative approximation method]]", "[[Vertex enumeration problem]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]"]
---

# Bentley–Ottmann algorithm

In computational geometry, the Bentley–Ottmann algorithm is a sweep line algorithm for listing all crossings in a set of line segments, i.e. it finds the intersection points (or, simply, intersections) of line segments. It extends the Shamos–Hoey algorithm, a similar previous algorithm for testing whether or not a set of line segments has any crossings. For an input consisting of 
  
    
      
        n
      
    
    
  
 line segments with 
  
    
      
        k
      
    
    
  
 crossings (or intersections), the Bentley–Ottmann algorithm takes time 
  
    
      
        
          
            O
          
        
        (
        n
        k
        log
         
        n
      
    
    
  
. In cases where 
  
    
      
        k
        
          
            o
          
        
        
          
            
              
                n
                
                  2
                
              
              
                 
                n
              
            
          
        
      
    
    
  
, this is an improvement on a naïve algorithm that tests every pair of segments, which takes 
  
    
      
        Θ
        
          n
          
            2
          
        
      
    
    
  
.
The algorithm was initially developed by Jon Bentley and Thomas Ottmann (1979); it is described in more detail in the textbooks Preparata & Shamos (1985), O'Rourke (1998), and de Berg et al. (2000). Although asymptotically faster algorithms are now known by Chazelle & Edelsbrunner (1992) and Balaban (1995), the Bentley–Ottmann algorithm remains a practical choice due to its simplicity and low memory requirements.

## Related

- [[Euclidean shortest path]]
- [[Multiple line segment intersection]]
- [[Progressive-iterative approximation method]]
- [[Vertex enumeration problem]]
- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bentley–Ottmann_algorithm