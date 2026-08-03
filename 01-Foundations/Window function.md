---
title: "Window function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Window_function"
wikipedia_categories: ["Digital signal processing", "Fourier analysis", "Signal estimation", "Types of functions"]
related: ["[[Almost periodic function]]", "[[Slepian function]]", "[[Basis function]]", "[[DFT matrix]]", "[[Dirac delta function]]", "[[Discrete cosine transform]]", "[[Discrete Fourier transform]]", "[[Discrete-time Fourier transform]]", "[[Fourier analysis]]", "[[Instantaneous phase and frequency]]"]
---

# Window function

In signal processing and statistics, a window function (also known as an apodization function or tapering function) is a mathematical function that is zero-valued outside of some chosen interval. Typically, window functions are symmetric around the middle of the interval, approach a maximum in the middle, and taper away from the middle. Mathematically, when another function or waveform/data-sequence is "multiplied" by a window function, the product is also zero-valued outside the interval: all that is left is the part where they overlap, the "view through the window".  Equivalently, and in actual practice, the segment of data within the window is first isolated, and then only that data is multiplied by the window function values.  Thus, tapering, not segmentation, is the main purpose of window functions.
The reasons for examining segments of a longer function include detection of transient events and time-averaging of frequency spectra.  The duration of the segments is determined in each application by requirements like time and frequency resolution.  But that method also changes the frequency content of the signal by an effect called spectral leakage.  Window functions allow us to distribute the leakage spectrally in different ways, according to the needs of the particular application.  There are many choices detailed in this article, but many of the differences are so subtle as to be insignificant in practice.
In typical applications, the window functions used are non-negative, smooth, "bell-shaped" curves. Rectangle, triangle, and other functions can also be used.  A more general definition of window functions does not require them to be identically zero outside an interval, as long as the product of the window multiplied by its argument is square integrable, and, more specifically, that the function goes sufficiently rapidly toward zero.

## Related

- [[Almost periodic function]]
- [[Slepian function]]
- [[Basis function]]
- [[DFT matrix]]
- [[Dirac delta function]]
- [[Discrete cosine transform]]
- [[Discrete Fourier transform]]
- [[Discrete-time Fourier transform]]
- [[Fourier analysis]]
- [[Instantaneous phase and frequency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Window_function