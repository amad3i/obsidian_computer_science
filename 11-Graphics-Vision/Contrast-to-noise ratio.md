---
title: "Contrast-to-noise ratio"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Contrast-to-noise_ratio"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Contrast-to-noise ratio

Contrast-to-noise ratio (CNR) is a measure used to determine image quality.  CNR is similar to the metric signal-to-noise ratio (SNR), but subtracts a term before taking the ratio. This is important when there is a significant bias in an image, such as from haze.  As can be seen in the picture at right, the intensity is rather high even though the features of the image are washed out by the haze.  Thus this image may have a high SNR metric, but will have a low CNR metric.
One way to define contrast-to-noise ratio is:

  
    
      
        C
        
          
            
              
                |
              
              
                S
                
                  A
                
              
              
                S
                
                  B
                
              
              
                |
              
            
            
              σ
              
                o
              
            
          
        
      
    
    
  

where SA and SB are signal intensities for signal producing structures A and B in the region of interest and σo is the standard deviation of the pure image noise.

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
- [[Atkinson dithering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Contrast-to-noise_ratio