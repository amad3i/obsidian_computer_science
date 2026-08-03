---
title: "Inverse depth parametrization"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Inverse_depth_parametrization"
wikipedia_categories: ["Computer vision"]
related: ["[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]", "[[Active contour model]]", "[[Active shape model]]", "[[Active vision]]"]
---

# Inverse depth parametrization

In computer vision, the inverse depth parametrization is a parametrization used in methods for 3D reconstruction from multiple images such as simultaneous localization and mapping (SLAM). Given a point 
  
    
      
        
          p
        
      
    
    
  
 in 3D space observed by a monocular pinhole camera from multiple views, the inverse depth parametrization of the point's position is a 6D vector that encodes the optical centre of the camera 
  
    
      
        
          
            c
          
          
            0
          
        
      
    
    
  
 when in first observed the point, and the position of the point along the ray passing through 
  
    
      
        
          p
        
      
    
    
  
 and 
  
    
      
        
          
            c
          
          
            0
          
        
      
    
    
  
.
Inverse depth parametrization generally improves numerical stability and allows to represent points with zero parallax. Moreover, the error associated to the observation of the point's position can be modelled with a Gaussian distribution when expressed in inverse depth. This is an important property required to apply methods, such as Kalman filters, that assume normality of the measurement error distribution. The major drawback is the larger memory consumption, since the dimensionality of the point's representation is doubled.

## Related

- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]
- [[Active contour model]]
- [[Active shape model]]
- [[Active vision]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Inverse_depth_parametrization