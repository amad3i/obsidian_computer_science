---
title: "Local ternary patterns"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_ternary_patterns"
wikipedia_categories: ["Computer science stubs", "Computer vision"]
related: ["[[N-jet]]", "[[Video imprint (computer vision)]]", "[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]", "[[Active contour model]]"]
---

# Local ternary patterns

Local ternary patterns (LTP) are an extension of local binary patterns (LBP). Unlike LBP, it does not threshold the pixels into 0 and 1, rather it uses a threshold constant to threshold pixels into three values. Considering k as the threshold constant, c as the value of the center pixel, a neighboring pixel p, the result of threshold is:

  
    
      
        
          
            
              
                
                  1
                  ,
                
                
                  
                    if 
                  
                  p
                  c
                  k
                
              
              
                
                  0
                  ,
                
                
                  
                    if 
                  
                  p
                  c
                  k
                  
                     and 
                  
                  p
                  c
                  k
                
              
              
                
                  1
                
                
                  
                    if 
                  
                  p
                  c
                  k
                
              
            
            
          
        
      
    
    
  

In this way, each thresholded pixel has one of the three values. Neighboring pixels are combined after thresholding into a ternary pattern. Computing a histogram of these ternary values will result in a large range, so the ternary pattern is split into two binary patterns. Histograms are concatenated to generate a descriptor double the size of LBP.

## Related

- [[N-jet]]
- [[Video imprint (computer vision)]]
- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]
- [[Active contour model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_ternary_patterns