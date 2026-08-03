---
title: "Image derivative"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Image_derivative"
wikipedia_categories: ["Generalizations of the derivative", "Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Arithmetic derivative]]"]
---

# Image derivative

Image derivatives can be computed by using small convolution filters of size 2 × 2 or 3 × 3, such as the  Laplacian, Sobel, Roberts and Prewitt operators. However, a larger mask will generally give a better approximation of the derivative and examples of such filters are Gaussian derivatives and Gabor filters. Sometimes high frequency noise needs to be removed and this can be incorporated in the filter so that the Gaussian kernel will act as a band pass filter. The use of Gabor filters in image processing has been motivated by some of its similarities to the perception in the human visual system.
The pixel value is computed as a convolution

  
    
      
        
          p
          
            u
          
          ′
        
        
          d
        
        G
      
    
    
  

where 
  
    
      
        
          d
        
      
    
    
  
 is the derivative kernel and 
  
    
      
        G
      
    
    
  
 is the pixel values in a region of the image and 
  
    
      
      
    
    
  
 is the operator that performs the convolution.

## Related

- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]
- [[Arithmetic derivative]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Image_derivative