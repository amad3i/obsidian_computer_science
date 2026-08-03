---
title: "Swizzling (computer graphics)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Swizzling_(computer_graphics)"
wikipedia_categories: ["Computer graphics", "Computer graphics stubs"]
related: ["[[4D reconstruction]]", "[[Color clock]]", "[[Colour banding]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Fillrate]]", "[[Glyph (data visualization)]]", "[[Gooch shading]]"]
---

# Swizzling (computer graphics)

In computer graphics, swizzles are a class of operations that transform vectors by rearranging components. Swizzles can also project from a vector of one dimensionality to a vector of another dimensionality, such as taking a three-dimensional vector and creating a two-dimensional or five-dimensional vector using components from the original vector. For example, if A = {1,2,3,4}, where the components are x, y, z, and w respectively, one could compute B = A.wwxy, whereupon B would equal {4,4,1,2}. Additionally, one could create a two-dimensional vector with A.wx or a five-dimensional vector with A.xyzwx. Combining vectors and swizzling can be employed in various ways. This is common in GPGPU applications. 
In terms of linear algebra, this is equivalent to multiplying by a matrix whose rows are standard basis vectors. If 
  
    
      
        A
        (
        1
        ,
        2
        ,
        3
        ,
        4
        
          
            T
          
        
      
    
    
  
, then swizzling 
  
    
      
        A
      
    
    
  
 as above looks like

  
    
      
        A
        .
        
        w
        w
        x
        y
        
          
            
              
                
                  0
                
                
                  0
                
                
                  0
                
                
                  1
                
              
              
                
                  0
                
                
                  0
                
                
                  0
                
                
                  1
                
              
              
                
                  1
                
                
                  0
                
                
                  0
                
                
                  0
                
              
              
                
                  0
                
                
                  1
                
                
                  0
                
                
                  0
                
              
            
          
        
        
          
            
              
                
                  1
                
              
              
                
                  2
                
              
              
                
                  3
                
              
              
                
                  4
                
              
            
          
        
        
          
            
              
                
                  4
                
              
              
                
                  4
                
              
              
                
                  1
                
              
              
                
                  2
                
              
            
          
        
        .
      
    
    

## Related

- [[4D reconstruction]]
- [[Color clock]]
- [[Colour banding]]
- [[Czekanowski distance]]
- [[Depth peeling]]
- [[Device-independent pixel]]
- [[Drop shadow]]
- [[Fillrate]]
- [[Glyph (data visualization)]]
- [[Gooch shading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Swizzling_(computer_graphics)