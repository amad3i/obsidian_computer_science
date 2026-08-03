---
title: "Interlacing (bitmaps)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Interlacing_(bitmaps)"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Interlacing (bitmaps)

In computing, interlacing (also known as interleaving) is a method of encoding a bitmap image such that a person who has partially received it sees a degraded copy of the entire image. When communicating over a slow communications link, this is often preferable to seeing a perfectly clear copy of one part of the image, as it helps the viewer decide more quickly whether to abort or continue the transmission.
Interlacing is supported by the following formats, where it is optional:

GIF interlacing stores the lines in the order 
  
    
      
        0
        ,
        8
        ,
        16
        ,
        …
        ,
        8
        n
        ,
         
        4
        ,
        12
        ,
        …
        ,
        8
        n
        4
        ,
         
        2
        ,
        6
        ,
        10
        ,
        14
        ,
        …
        ,
        4
        n
        2
        ,
         
        1
        ,
        3
        ,
        5
        ,
        7
        ,
        9
        ,
        …
        ,
        2
        n
        1
        .
      
    
    
  

PNG uses the Adam7 algorithm, which interlaces in both the vertical and horizontal direction.
TGA uses two optional interlacing algorithms:
Two-way: 
  
    
      
        0
        ,
        2
        ,
        4
        ,
        …
        ,
        2
        n
        ,
         
        1
        ,
        3
        ,
        …
        ,
        2
        n
        1
        ,
      
    
    
  

And four-way: 
  
    
      
        0
        ,
        4
        ,
        8
        ,
        …
        ,
        4
        n
        ,
         
        1
        ,
        5
        ,
        …
        ,
        4
        n
        1
        ,
         
        2
        ,
        6
        ,
        …
        ,
         
        4
        n
        2
        ,
        3
        ,
        7
        ,
        …
        ,
        4
        n
        3
        .
      
    
    
  

JPEG, JPEG 2000, and JPEG XR (actually using a frequency decomposition hierarchy rather than interlacing of pixel values)
PGF (also using a frequency decomposition)
Interlacing is a form of incremental decoding, because the image can be loaded incrementally. Another form of incremental decoding is progressive scan. In progressive scan the loaded image is decoded line for line, so instead of becoming incrementally clearer it becomes incrementally larger. The main difference between the interlace concept in bitmaps and in video is that even progressive bitmaps can be loaded over multiple frames.
For example: Interlaced GIF is a GIF image that seems to arrive on your display like an image coming through a slowly opening Venetian blind. A fuzzy outline of an image is gradually replaced by seven successive waves of bit streams that fill in the missing lines until the image arrives at its full resolution.
Interlaced graphics were once widely used in web design and before that in the distribution of graphics files over bulletin board systems and other low-speed communications methods. The practice is much less common today, as common broadband internet connections allow most images to be downloaded to the user's screen nearly instantaneously, and interlacing is usually an inefficient method of encoding images.
Interlacing has been criticized because it may not be clear to viewers when the image has finished rendering, unlike non-interlaced rendering, where progress is apparent (remaining data appears as blank). Also, the benefits of interlacing to those on low-speed connections may be outweighed by having to download a larger file, as interlaced images typically do not compress as well.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interlacing_(bitmaps)