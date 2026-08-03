---
title: "Media processor"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Media_processor"
wikipedia_categories: ["Central processing unit", "Coprocessors", "Digital electronics", "Digital signal processing", "Digital signal processors"]
related: ["[[Digital signal processor]]", "[[Central processing unit]]", "[[Digital signal controller]]", "[[Digital signal processing]]", "[[Multidimensional DSP with GPU acceleration]]", "[[Numerically controlled oscillator]]", "[[Oversampled binary image sensor]]", "[[Sensor hub]]", "[[Vector processor]]", "[[2D adaptive filters]]"]
---

# Media processor

A media processor, mostly used as an image/video processor, is a microprocessor-based system-on-a-chip (SOC) which is designed to deal with digital streaming data in real-time (e.g. display refresh) rates. These devices can also be considered a class of digital signal processors (DSPs).
Unlike graphics processing units (GPUs), which are used for computer displays, media processors are targeted at digital televisions and set-top boxes.
The streaming digital media classes include:

uncompressed video
compressed digital video - e.g. MPEG-1, MPEG-2, MPEG-4
digital audio- e.g. PCM, AAC
Such SOCs are composed of:

a microprocessor optimized to deal with these media datatypes
a memory interface
streaming media interfaces
specialized functional units to help deal with the various digital media codecs
The microprocessor might have these optimizations:

vector processing or SIMD functional units to efficiently deal with these media datatypes
DSP-like features
Previous to media processors, these streaming media datatypes were processed using fixed-function, hardwired ASICs, which could not be updated in the field. This was a big disadvantage when any of the media standards were changed. Since media processors are software programmed devices, the
processing done on them could be updated with new software releases. This allowed new generations of systems to be created without hardware redesign. For set-top boxes this even allows for the possibility of in-the-field upgrade by downloading of new software through cable or satellite networks.    
Companies that pioneered the idea of media processors (and created the marketing term of media processor) included:

MicroUnity MediaProcessor - Cancelled in 1996 before introduction
IBM Mfast - Described at the Microprocessor Forum in 1995, planned to ship in mid-1997 but was cancelled before introduction
Equator Semiconductor BSP line - their processors are used in Hitachi televisions, company acquired by Pixelworks
Chromatic Research MPact line - their products were used on some PC graphics cards in the mid-1990s, company acquired by ATI Technologies
Philips TriMedia line - used in Philips, Dell, Sony, etc. consumer electronics, Philips Semiconductors split off from Philips and became NXP Semiconductors in 2006
Consumer electronics companies have successfully dominated this market by designing their own media processors and integrating them into their video products. Companies such as Philips, Samsung, Matsushita, Fujitsu, Mitsubishi have their own in-house media processor devices. 
Newer generations of such devices now use various forms of multiprocessing—multiple CPUs or DSPs, in order to deal with the vastly increased computational needs when dealing with high-definition television signals.

## Related

- [[Digital signal processor]]
- [[Central processing unit]]
- [[Digital signal controller]]
- [[Digital signal processing]]
- [[Multidimensional DSP with GPU acceleration]]
- [[Numerically controlled oscillator]]
- [[Oversampled binary image sensor]]
- [[Sensor hub]]
- [[Vector processor]]
- [[2D adaptive filters]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Media_processor