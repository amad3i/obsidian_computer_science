---
title: "Closed-loop controller"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Closed-loop_controller"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Closed-loop controller

A closed-loop controller or feedback controller is a control loop which incorporates feedback, in contrast to an open-loop controller or non-feedback controller.
A closed-loop controller uses feedback to control states or outputs of a dynamical system. Its name comes from the information path in the system: process inputs (e.g., voltage applied to an electric motor) have an effect on the process outputs (e.g., speed or torque of the motor), which is measured with sensors and processed by the controller; the result (the control signal) is "fed back" as input to the process, closing the loop.
In the case of linear feedback systems, a control loop including sensors, control algorithms, and actuators is arranged in an attempt to regulate a variable at a setpoint (SP).  An everyday example is the cruise control on a road vehicle; where external influences such as hills would cause speed changes, and the driver has the ability to alter the desired set speed. The PID algorithm in the controller restores the actual speed to the desired speed in an optimum way, with minimal delay or overshoot, by controlling the power output of the vehicle's engine.
Control systems that include some sensing of the results they are trying to achieve are making use of feedback and can adapt to varying circumstances to some extent. Open-loop control systems do not make use of feedback, and run only in pre-arranged ways.
Closed-loop controllers have the following advantages over open-loop controllers:

disturbance rejection (such as hills in the cruise control example above)
guaranteed performance even with model uncertainties, when the model structure does not match perfectly the real process and the model parameters are not exact
unstable processes can be stabilized
reduced sensitivity to parameter variations
improved reference tracking performance
improved rectification of random fluctuations
In some systems, closed-loop and open-loop control are used simultaneously. In such systems, the open-loop control is termed feedforward and serves to further improve reference tracking performance.
A common closed-loop controller architecture is the PID controller.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Closed-loop_controller