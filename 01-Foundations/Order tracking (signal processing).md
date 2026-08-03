---
title: "Order tracking (signal processing)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Order_tracking_(signal_processing)"
wikipedia_categories: ["Dynamics (mechanics)", "Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Order tracking (signal processing)

In rotordynamics, order tracking is a family of signal processing tools aimed at transforming a measured signal from time domain to angular (or order) domain. These techniques are applied to asynchronously sampled signals (i.e. with a constant sample rate in Hertz) to obtain the same signal sampled at constant angular increments of a reference shaft. In some cases the outcome of the Order Tracking is directly the Fourier transform of such angular domain signal, whose frequency counterpart is defined as "order". Each order represents a fraction of the angular velocity of the reference shaft.
Order tracking is based on a velocity measurement, generally obtained by means of a tachometer or encoder, needed to estimate the instantaneous velocity and/or the angular position of the shaft.
Three main families of computed order tracking techniques have been developed in the past: Computed Order Tracking (COT),  Vold-Kalman Filter (VKF) and Order Tracking Transforms.
Order tracking refers to a signal processing technique used to extract the periodic content of a signal and track its frequency variations over time. This technique is often used in vibration analysis and monitoring of rotating machinery, such as engines, turbines, and pumps.
In order to track the order of a signal, the signal is first transformed into the frequency domain using techniques such as the Fourier transform. The resulting frequency spectrum shows the frequency content of the signal. From the frequency spectrum, it is possible to identify the dominant frequency components, which correspond to the various orders of the rotating machinery.
Once the orders are identified, a tracking algorithm is used to track the frequency variations of each order over time. This is done by comparing the frequency content of the signal at different time instants and identifying the shifts in the frequency components.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Order_tracking_(signal_processing)