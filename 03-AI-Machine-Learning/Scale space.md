---
title: "Scale space"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Scale_space"
wikipedia_categories: ["Computer vision", "Image processing"]
related: ["[[3D selfie]]", "[[Class activation mapping]]", "[[Color normalization]]", "[[Computer vision]]", "[[Contextual image classification]]", "[[Digital image processing]]", "[[Document mosaicing]]", "[[Dynamic texture]]", "[[Image destriping]]", "[[Image formation]]"]
---

# Scale space

Scale-space theory is a framework for multi-scale signal representation developed by the computer vision, image processing and signal processing communities with complementary motivations from physics and biological vision. It is a formal theory for handling image structures at different scales, by representing an image as a one-parameter family of smoothed images, the scale-space representation, parametrized by the size of the smoothing kernel used for suppressing fine-scale structures. The parameter 
  
    
      
        t
      
    
    
  
 in this family is referred to as the scale parameter, with the interpretation that image structures of spatial size smaller than about 
  
    
      
        
          
            t
          
        
      
    
    
  
 have largely been smoothed away in the scale-space level at scale 
  
    
      
        t
      
    
    
  
.
The main type of scale space is the linear (Gaussian) scale space, which has wide applicability as well as the attractive property of being possible to derive from a small set of scale-space axioms.  The corresponding scale-space framework encompasses a theory for Gaussian derivative operators, which can be used as a basis for expressing a large class of visual operations for computerized systems that process visual information.  This framework also allows visual operations to be made scale invariant, which is necessary for dealing with the size variations that may occur in image data, because real-world objects may be of different sizes and in addition the distance between the object and the camera may be unknown and may vary depending on the circumstances.

## Related

- [[3D selfie]]
- [[Class activation mapping]]
- [[Color normalization]]
- [[Computer vision]]
- [[Contextual image classification]]
- [[Digital image processing]]
- [[Document mosaicing]]
- [[Dynamic texture]]
- [[Image destriping]]
- [[Image formation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scale_space