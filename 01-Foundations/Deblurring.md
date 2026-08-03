---
title: "Deblurring"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Deblurring"
wikipedia_categories: ["Image processing", "Signal processing stubs"]
related: ["[[Decorrelation]]", "[[Image destriping]]", "[[Image restoration by artificial intelligence]]", "[[Non-separable wavelet]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Adjacent channel power ratio]]"]
---

# Deblurring

Deblurring is the process of removing blurring artifacts from images. Deblurring recovers a sharp image S from a blurred image B, where S is convolved with K (the blur kernel) to generate B. Mathematically, this can be represented as 
  
    
      
        B
        S
        K
      
    
    
  
 (where * represents convolution). 
While this process is sometimes known as unblurring, deblurring is the correct technical word. 
The blur K is typically modeled as point spread function and is convolved with a hypothetical sharp image S to get B, where both the S (which is to be recovered) and the point spread function K are unknown. This is an example of an inverse problem. In almost all cases, there is insufficient information in the blurred image to uniquely determine a plausible original image, making it an ill-posed problem. In addition the blurred image contains additional noise which complicates the task of determining the original image. This is generally solved by the use of a regularization term to attempt to eliminate implausible solutions. This problem is analogous to echo removal in the signal processing domain. Nevertheless, when coherent beam is used for imaging, the point spread function can be modeled mathematically. By proper deconvolution of the point spread function K and the blurred image B, the blurred image B can be deblurred (unblur) and the sharp image S can be recovered.

## Related

- [[Decorrelation]]
- [[Image destriping]]
- [[Image restoration by artificial intelligence]]
- [[Non-separable wavelet]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Adjacent channel power ratio]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deblurring