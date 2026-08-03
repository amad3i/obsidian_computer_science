---
title: "Input shaping"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Input_shaping"
wikipedia_categories: ["Control theory", "Cybernetics", "Dynamics (mechanics)", "Mechanical vibrations"]
related: ["[[Impulse vector]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[Bicycle and motorcycle dynamics]]", "[[Control reconfiguration]]", "[[Fractional-order control]]", "[[Intermittent control]]", "[[Machine learning control]]", "[[Negative feedback]]", "[[Optogenetics]]"]
---

# Input shaping

In control theory, input shaping is an open-loop control technique for reducing vibrations in computer-controlled machines. The method works by creating a command signal that cancels its own vibration. That is, a vibration excited by previous parts of the command signal is cancelled by vibration excited by latter parts of the command.
Input shaping is implemented by convolving a sequence of impulses, known as an input shaper, with any arbitrary command. The shaped command that results from the convolution is then used to drive the system.
If the impulses in the shaper are chosen correctly, then the shaped command will excite less residual vibration than the unshaped command. The amplitudes and time locations of the impulses are obtained from the system's natural frequencies and damping ratios. Shaping can be made very robust to errors in the system parameters.

## Related

- [[Impulse vector]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[Bicycle and motorcycle dynamics]]
- [[Control reconfiguration]]
- [[Fractional-order control]]
- [[Intermittent control]]
- [[Machine learning control]]
- [[Negative feedback]]
- [[Optogenetics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Input_shaping