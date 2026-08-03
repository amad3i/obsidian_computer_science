---
title: "Quaternions and spatial rotation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Quaternions_and_spatial_rotation"
wikipedia_categories: ["3D computer graphics", "Quaternions", "Rigid bodies mechanics", "Rotation in three dimensions"]
related: ["[[Conversion between quaternions and Euler angles]]", "[[Gimbal lock]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]"]
---

# Quaternions and spatial rotation

Unit quaternions, known as versors, provide a convenient mathematical notation for representing spatial orientations and rotations of elements in three dimensional space (3D rotations). This is a generalization of the use of unit complex numbers for 2D rotations. Specifically, quaternions encode information about an axis-angle rotation about an arbitrary axis. Rotation and orientation quaternions have applications in computer graphics, computer vision, robotics, navigation, molecular dynamics, flight dynamics, orbital mechanics of satellites, and crystallographic texture analysis.
When used to represent rotation, unit quaternions are also called rotation quaternions as they represent the 3D rotation group. When used to represent an orientation or attitude (body rotation relative to a reference coordinate system), they are called orientation quaternions or attitude quaternions. A spatial rotation in the amount of 
  
    
      
        θ
      
    
    
  
 radians about a fixed unit axis 
  
    
      
        X
        ,
        Y
        ,
        Z
      
    
    
  
 that denotes the Euler axis is given by the quaternion 
  
    
      
        C
        ,
        X
        
        S
        ,
        Y
        
        S
        ,
        Z
        
        S
      
    
    
  
, where 
  
    
      
        C
        cos
         
        θ
        
          /
        
        2
      
    
    
  
 and 
  
    
      
        S
        sin
         
        θ
        
          /
        
        2
      
    
    
  
.
Compared to rotation matrices, quaternions are more compact, efficient, and numerically stable. Compared to Euler angles, they are simpler to compose. However, they are not as intuitive and easy to understand and, due to the periodic nature of sine and cosine, rotation angles differing precisely by the natural period will be encoded into identical quaternions and recovered angles in radians will be limited to 
  
    
      
        0
        ,
        2
        π
      
    
    
  
.

## Related

- [[Conversion between quaternions and Euler angles]]
- [[Gimbal lock]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quaternions_and_spatial_rotation