---
title: "Expeed"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Expeed"
wikipedia_categories: ["Camera firmware", "Digital photography", "Fujitsu microprocessors", "Image processors", "Nikon cameras", "Parallel computing", "SIMD computing"]
related: ["[[Milbeaut]]", "[[FR-V (microprocessor)]]", "[[Automatic vectorization]]", "[[Single instruction, multiple data]]", "[[Single instruction, multiple threads]]", "[[SWAR]]", "[[Thinking Machines Corporation]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]"]
---

# Expeed

The Nikon Expeed image/video processors (often styled EXPEED) are media processors for Nikon's digital cameras. 
They perform a large number of tasks: 

Bayer filtering
demosaicing
image sensor corrections/dark-frame subtraction
image noise reduction
image sharpening
image scaling
gamma correction
image enhancement/Active D-Lighting
colorspace conversion
chroma subsampling
framerate conversion
lens distortion/chromatic aberration correction
image compression/JPEG encoding
video compression
display/video interface driving
digital image editing
face detection
audio processing/compression/encoding and
computer data storage/data transmission.
Expeed's multi-processor system on a chip solution integrates an image processor in multi-core processor architecture, with each single processor-core able to compute many instructions/operations in parallel. Storage and display interfaces and other modules are added and a digital signal processor (DSP) increases the number of simultaneous computations. On-chip 32-bit microcontroller initiates and controls the operation and data transfers of all processors, modules, interfaces and can be seen as the main control unit of the camera.
In each generation Nikon uses different versions for its professional and consumer DSLRs / MILCs, whereas its compact cameras use completely different architectures. This is different from for example Canons DIGIC: its professional DSLRs double the processors of its consumer DSLR series. The Expeed is an application-specific integrated circuit (ASIC) built by Socionext specifically for Nikon designs according to Nikon specifications.

## Related

- [[Milbeaut]]
- [[FR-V (microprocessor)]]
- [[Automatic vectorization]]
- [[Single instruction, multiple data]]
- [[Single instruction, multiple threads]]
- [[SWAR]]
- [[Thinking Machines Corporation]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Expeed