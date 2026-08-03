---
title: "Box blur"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Box_blur"
wikipedia_categories: ["Image processing", "Photography stubs"]
related: ["[[Epsilon photography]]", "[[Gigamacro]]", "[[Image histogram]]", "[[Image subtraction]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]"]
---

# Box blur

A box blur (also known as a box linear filter) is a spatial domain linear filter in which each pixel in the resulting image has a value equal to the average value of its neighboring pixels in the input image. It is a form of low-pass ("blurring")  filter. A 3 by 3 box blur ("radius 1") can be written as matrix

  
    
      
        
          
            1
            9
          
        
        
          
            
              
                
                  1
                
                
                  1
                
                
                  1
                
              
              
                
                  1
                
                
                  1
                
                
                  1
                
              
              
                
                  1
                
                
                  1
                
                
                  1
                
              
            
          
        
        .
      
    
    
  

Due to its property of using equal weights, it can be implemented using a much simpler accumulation algorithm, which is significantly faster than using a sliding-window algorithm.
Box blurs are frequently used to approximate a Gaussian blur. By the central limit theorem, repeated application of a box blur will approximate a Gaussian blur.
In the frequency domain, a box blur has zeros and negative components. That is, a sine wave with a period equal to the size of the box will be blurred away entirely, and wavelengths shorter than the size of the box may be phase-reversed, as seen when two bokeh circles touch to form a bright spot where there would be a dark spot between two bright spots in the original image.

## Related

- [[Epsilon photography]]
- [[Gigamacro]]
- [[Image histogram]]
- [[Image subtraction]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Box_blur