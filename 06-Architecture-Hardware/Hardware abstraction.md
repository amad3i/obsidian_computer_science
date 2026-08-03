---
title: "Hardware abstraction"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Hardware_abstraction"
wikipedia_categories: ["Booting", "Device drivers", "Firmware", "Operating system technology"]
related: ["[[Board support package]]", "[[Devicetree]]", "[[Execute in place]]", "[[Mode setting]]", "[[Network redirector]]", "[[Single-user mode]]", "[[User space and kernel space]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]"]
---

# Hardware abstraction

A hardware abstraction is software that provides access to hardware in a way that hides details that might otherwise make using the hardware difficult. Typically, access is provided via a software interface that allows devices that share a level of similarity to be accessed via the same software actions even though the devices provide different hardware interfaces. A hardware abstraction can support the development of cross-platform applications. 
Early software was developed without a hardware abstraction, which required a developer to understand multiple devices in order to provide compatibility. With hardware abstraction, the software leverages the abstraction to access significantly different hardware via the same interface. The abstraction (often implemented in the operating system) then performs the hardware-specific operations. This allows software to be compatible with all devices supported by the abstraction.
Consider a joystick device, of which there are many physical implementations. It could be accessible via an application programming interface (API) that supports common operations such as moving, firing, configuring sensitivity, and so on across variety of different joysticks. A Joystick abstraction hides details (e.g., register format, I2C address) so programmers using the abstraction do not need to understand details regarding the device's physical interface. This also allows code reuse since the same code can process standardized messages from any kind of implementation which supplies the joystick abstraction. For example, a "nudge forward" can be from a potentiometer or from a capacitive touch sensor that recognizes "swipe" gestures, as long as they both provide a signal related to "movement".
As physical limitations may vary with hardware, an API can do little to hide that, other than by assuming a "least common denominator" model. Thus, certain deep architectural decisions from the implementation may become relevant to users of a particular instantiation of an abstraction.
A good metaphor is the abstraction of transportation. Both bicycling and driving a car are transportation. They both have commonalities (e.g., it must be steered) and physical differences (e.g., power source). One can always specify the abstraction "drive to" and let the implementer decide whether bicycling or driving a car is best. The "wheeled terrestrial transport" function is abstracted and the details of "how to drive" are encapsulated.

## Related

- [[Board support package]]
- [[Devicetree]]
- [[Execute in place]]
- [[Mode setting]]
- [[Network redirector]]
- [[Single-user mode]]
- [[User space and kernel space]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hardware_abstraction