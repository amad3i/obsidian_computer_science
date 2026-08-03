---
title: "Systems development life cycle"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Systems_development_life_cycle"
wikipedia_categories: ["Computing terminology", "Software development process", "Software engineering", "Systems engineering"]
related: ["[[Behavior tree]]", "[[Capability Maturity Model Integration]]", "[[Configuration management]]", "[[Continuous configuration automation]]", "[[Developer experience]]", "[[Domain engineering]]", "[[Easy Approach to Requirements Syntax]]", "[[Infrastructure as code]]", "[[Interface control document]]", "[[Meta-process modeling]]"]
---

# Systems development life cycle

The systems development life cycle (SDLC) describes the typical phases and progression between phases during the development of a computer-based system. These phases progress from inception to retirement. At base, there is just one life cycle, but the taxonomy used to describe it may vary; the cycle may be classified into different numbers of phases and various names may be used for those phases. The SDLC is analogous to the life cycle of a living organism from its birth to its death. In particular, the SDLC varies by system in much the same way that each living organism has a unique path through its life.
The SDLC does not prescribe how engineers should go about their work to move the system through its life cycle. Prescriptive techniques are referred to using various terms such as methodology, model, framework, and formal process.
Other terms are used for the same concept as SDLC, including software development life cycle (also SDLC), application development life cycle (ADLC), and system design life cycle (also SDLC). These other terms focus on a different scope of development and are associated with different prescriptive techniques, but are about the same essential life cycle.
The term "life cycle" is often written without a space, as "lifecycle", with the former more popular in the past and in non-engineering contexts. The acronym SDLC was coined when the longer form was more popular and has remained associated with the expansion, even though the shorter form is popular in engineering. Also, SDLC is relatively unique as opposed to the TLA SDL, which is highly overloaded.

== Phases ==

Depending on the source, the SDLC is described as having different phases and using different terms. Even so, there are common aspects. The following attempts to describe notable phases using notable terminology. The phases are somewhat ordered by the natural sequence of development, although they can be overlapping and iterative.

=== Conceptualization ===
During conceptualization (a.k.a. conceptual design, system investigation, feasibility), options and priorities are considered. A feasibility study can determine whether the development effort is worthwhile via activities such as understanding user needs, cost estimation, benefit analysis, and resource analysis. A study should address operational, financial, technical, human factors, and legal/political concerns.

=== Requirements analysis ===
Requirements analysis (a.k.a. preliminary design) involves understanding the problem and determining what is needed. Often this involves engaging users to define the requirements and recording them in a document known as a requirements specification.

=== Design ===
During the design phase (a.k.a. detail design), a solution is planned. The plan can include relatively high-level information such as describing the major components of the system. The plan can include relatively low-level information such as describing functions, screen layout, business rules, and process flow. The design phase is informed by the requirements of the system. The design must satisfy each requirement. The design may be recorded in textual documents as well as functional hierarchy diagrams, example screen images, business rules, process diagrams, pseudo-code, and data models.

=== Construction ===
During construction (a.k.a. implementation, production), the system is realized. Based on the design, hardware and software components are created and integrated. This phase includes testing sub-components, components and the integration of some components, but typically does not include testing at the complete system level. This phase may include the development of training materials, including user manuals and help files.

=== Acceptance ===
The acceptance phase (a.k.a. system testing) is about  testing the complete system to ensure that it meets customer expectations (requirements).

=== Deployment ===
The deployment phase (a.k.a. implementation) involves the logistics of delivery to the customer. Some systems are deployed as a single instance (i.e.  in the cloud), and deployment may be ad hoc and manual. Some systems are built in quantity and are associated with manufacturing process and commissioning. This phase may include training users to use the system. It may include transitioning future development to support staff.

=== Maintenance ===
During the maintenance phase (a.k.a. operation, utilization, support) development is largely inactive, although this phase does include customer support for resolving user issues and recording suggestions for improvement. Fixes and enhancements are handled by returning to the first phase, conceptualization. For minor changes, the cycle may be significantly abbreviated compared to initial development.

=== Decommission ===
Decommission (a.k.a. disposition, retirement, phase-out) is when the system is removed from use, i.e., when it reaches  end-of-life.

== Practices ==

=== Management and control ===

SDLC phase objectives are described in this section with key deliverables, a description of recommended tasks, and a summary of related control objectives for effective management. It is critical for the project manager to establish and monitor control objectives while executing projects. Control objectives are clear statements of the desired result or purpose and should be defined and monitored throughout a project. Control objectives can be grouped into major categories (domains), and relate to the SDLC phases as shown in the figure.
To manage and control a substantial SDLC initiative, a work breakdown structure (WBS) captures and schedules the work. The WBS and all programmatic material should be kept in the "project description" section of the project notebook. The project manager chooses a WBS format that best describes the project.
The diagram shows that coverage spans numerous phases of the SDLC, but the associated MCD (Management Control Domains) show mappings to SDLC phases. For example, Analysis and Design is primarily performed as part of the Acquisition and Implementation Domain, and System Build and Prototype is primarily performed as part of delivery and support.

=== Work breakdown structured organization ===

The upper section of the WBS provides an overview of the project scope and timeline. It should also summarize the major phases and milestones. The middle section is based on the SDLC phases. WBS elements consist of milestones and tasks to be completed rather than activities to be undertaken, and have a deadline. Each task has a measurable output (e.g., an analysis document). A WBS task may rely on one or more activities (e.g., coding). Parts of the project needing support from contractors should have a statement of work (SOW). The development of an SOW does not occur during a specific phase of SDLC but is developed to include the work from the SDLC process that may be conducted by contractors.

=== Baselines ===
Baselines are established after four of the five phases of the SDLC, and are critical to the iterative nature of the model. Baselines become milestones.

functional baseline: established after the conceptual design phase.
allocated baseline: established after the preliminary design phase.
product baseline: established after the detailed design and development phase.
updated product baseline: established after the production construction phase.
In the following diagram, these stages are divided into ten steps, from definition to creation and modification of IT work products:

== See also ==
Application lifecycle management – Product management of computer programs throughout their development lifecycles
Decision cycle – Sequence of steps for decision-making
IPO model – Input-process-output approach
Object-oriented analysis and design – Software development methodology
Program lifecycle phase
Software development process – Process by which software is developed
Software release life cycle – Stages in development and support of computer software
Systems analysis and design (disambiguation)

== References ==

== Further reading ==
Cummings, Haag (2006). Management Information Systems for the Information Age. Toronto, McGraw-Hill Ryerson
Beynon-Davies P. (2009). Business Information Systems. Palgrave, Basingstoke. ISBN 978-0-230-20368-6
Computer World, 2002, Retrieved on June 22, 2006, from the World Wide Web:
Management Information Systems, 2005, Retrieved on June 22, 2006, from the World Wide Web:

== External links ==

The Agile System Development Lifecycle
Pension Benefit Guaranty Corporation – Information Technology Solutions Lifecycle Methodology
DoD Integrated Framework Chart IFC (front, back)
FSA Life Cycle Framework
HHS Enterprise Performance Life Cycle Framework
The Open Systems Development Life Cycle
System Development Life Cycle Evolution Modeling
Zero Deviation Life Cycle
Integrated Defense AT&L Life Cycle Management Chart, the U.S. DoD form of this concept.

## Related

- [[Behavior tree]]
- [[Capability Maturity Model Integration]]
- [[Configuration management]]
- [[Continuous configuration automation]]
- [[Developer experience]]
- [[Domain engineering]]
- [[Easy Approach to Requirements Syntax]]
- [[Infrastructure as code]]
- [[Interface control document]]
- [[Meta-process modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Systems_development_life_cycle