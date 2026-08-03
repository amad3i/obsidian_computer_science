---
title: "Frequency response"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Frequency_response"
wikipedia_categories: ["Audio amplifier specifications", "Control theory", "Signal processing"]
related: ["[[Asymptotic gain model]]", "[[Derivation of the Routh array]]", "[[Dynamic range]]", "[[First-order hold]]", "[[Head-related transfer function]]", "[[Higher-order sinusoidal input describing function]]", "[[Masreliez's theorem]]", "[[Negative feedback]]", "[[Norator]]", "[[Nullator]]"]
---

# Frequency response

In signal processing and electronics, the frequency response of a system is the quantitative measure of the magnitude and phase of the output as a function of input frequency. The frequency response is widely used in the design and analysis of systems, such as audio equipment and control systems, where they simplify mathematical analysis by converting governing differential equations into algebraic equations. In an audio system, it may be used to minimize audible distortion by designing components (such as microphones, amplifiers and loudspeakers) so that the overall response is as flat (uniform) as possible across the system's bandwidth. In control systems, such as a vehicle's cruise control, it may be used to assess system stability, often through the use of Bode plots. Systems with a specific frequency response can be designed using analog and digital filters.
The frequency response characterizes systems in the frequency domain, just as the impulse response characterizes systems in the time domain. In linear systems (or as an approximation to a real system, neglecting second-order non-linear properties), either response completely describes the system, and thus there is a one-to-one correspondence: the frequency response is the Fourier transform of the impulse response. The frequency response allows simpler analysis of cascaded systems such as multistage amplifiers, as the response of the overall system can be found through multiplication of the individual stages' frequency responses (as opposed to convolution of the impulse response in the time domain). The frequency response is closely related to the transfer function in linear systems, which is the Laplace transform of the impulse response. They are equivalent when the real part 
  
    
      
        σ
      
    
    
  
 of the transfer function's complex variable 
  
    
      
        s
        σ
        j
        ω
      
    
    
  
 is zero.

## Related

- [[Asymptotic gain model]]
- [[Derivation of the Routh array]]
- [[Dynamic range]]
- [[First-order hold]]
- [[Head-related transfer function]]
- [[Higher-order sinusoidal input describing function]]
- [[Masreliez's theorem]]
- [[Negative feedback]]
- [[Norator]]
- [[Nullator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Frequency_response