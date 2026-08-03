---
title: "Semiconductor process simulation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Semiconductor_process_simulation"
wikipedia_categories: ["Electronic design automation", "Simulation"]
related: ["[[1-in-3-SAT]]", "[[Activation strain model]]", "[[AlphaChip]]", "[[And-inverter graph]]", "[[Artificial life]]", "[[Ashfield House]]", "[[Asynchronous system]]", "[[AXIS Flight Training Systems]]", "[[Barnes–Hut simulation]]", "[[Behavior authoring]]"]
---

# Semiconductor process simulation

Semiconductor process simulation is the modeling of the fabrication of semiconductor devices such as transistors. It is a branch of electronic design automation, and part of a sub-field known as technology CAD (TCAD).

The ultimate goal of process simulation is an accurate prediction of the active dopant distribution, the stress distribution and the device geometry. Process simulation is typically used as an input for device simulation, the modeling of device electrical characteristics. Collectively process and device simulation form the core tools for the design phase known as technology computer aided design (TCAD). Considering the integrated circuit design process as a series of steps with decreasing levels of abstraction, logic synthesis would be at the highest level and TCAD, being closest to fabrication, would be the phase with the least amount of abstraction.  Because of the detailed physical modeling involved, process simulation is almost exclusively used to aid in the development of single devices whether discrete or as a part of an integrated circuit.
The fabrication of integrated circuit devices requires a series of processing steps called a process flow.  Process simulation involves modeling all essential steps in the process flow in order to obtain dopant and stress profiles and, to a lesser extent, device geometry.  The input for process simulation is the process flow and a layout.  The layout is selected as a linear cut in a full layout for a 2D simulation or a rectangular cut from the layout for a 3D simulation.
TCAD has traditionally focused mainly on the transistor fabrication part of the process flow ending with the formation of source and drain contacts—also known as front end of line manufacturing.   Back end of line manufacturing, e.g. interconnect and dielectric layers are not considered.  One reason for delineation is the availability of powerful analysis tools such as electron microscopy techniques, scanning electron microscopy (SEM) and transmission electron microscopy (TEM), which allow for accurate measurement of device geometry.  There are no similar tools available for accurate high resolution measurement of dopant or stress profiles.
Nevertheless, there is growing interest to investigate the interaction between front end and back end manufacturing steps.  For example, back end manufacturing may cause stress in the transistor region changing device performance.   These interactions will stimulate the need for better interfaces to back end simulation tools or lead to integration of some of those capabilities into TCAD tools.
In addition to the recent expanding scope of process simulation, there has always been a desire to have more accurate simulations.  However, simplified physical models have been most commonly used in order to minimize computation time.  But, shrinking device dimensions put increasing demands on the accuracy of dopant and stress profiles so new process models are added for each generation of devices to match new accuracy demands.  Many of the models were conceived by researchers long before they were needed, but sometimes new effects are only recognized and understood once process engineers discover a problem and experiments are performed.  In any case, the trend of adding more physical models and considering more detailed physical effects will continue and may accelerate.

## Related

- [[1-in-3-SAT]]
- [[Activation strain model]]
- [[AlphaChip]]
- [[And-inverter graph]]
- [[Artificial life]]
- [[Ashfield House]]
- [[Asynchronous system]]
- [[AXIS Flight Training Systems]]
- [[Barnes–Hut simulation]]
- [[Behavior authoring]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semiconductor_process_simulation