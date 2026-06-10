---
title: "PhD Project 3 (DTU)"
permalink: /projects/phd-project-3/
---

## Open source Fog Node: hardware support for virtualization

This position has been filled.

**Host:** [Technical University of Denmark (DTU)](/partners/dtu/), [Embedded Systems Engineering (ESE)](http://www.compute.dtu.dk/english/research/ESE) section.

- Main supervisor: Prof. Martin Schoeberl, [masca@dtu.dk](mailto:masca@dtu.dk) (contact person)
- Co-supervisor: Prof. Jens Sparsø, jspa@dtu.dk

**Requirements:**

- [Mandatory requirements for all PhD positions](/job-requirements/)
- Master’s in Computer Science or equivalent
- Please contact the main supervisor for additional requirements

**Objectives:**

1. Develop and evaluate time-predictable hardware mechanisms to support virtualization, such as time-predictable virtual memory and time-predictable virtualization of I/O
2. Develop an open source implementation of a Fog Node hardware, with these virtualization mechanisms

**Expected Results**:

- Open-source prototype implementation of a Fog Node (FN) hardware, extending the T-CREST platform based on PATMOS processors
- Time-predictable virtualization of I/O devices and services
- Physical virtualization through manycore processors power down and up
- Segment based memory protection with time-predictable address translation
- Cache partitioning to remove cache related preemption delays
- Integration and evaluation of these hardware support mechanisms into PikeOS.

**Planned visits and collaboration:**

- SYSGO (Dr. Henrik Theiling): Explore hardware needs for virtualization; Port PikeOS to developed FN.

**Description:**

Current multicore processors support virtualization that is optimized for  
average case performance. Techniques such as paging and address translation  
caching with a TLB are hardly time-predictable. Within this PhD project  
time-predictable hardware mechanism will be developed to support  
virtualization. The project will extend the [T-CREST platform](https://github.com/t-crest).

**Relevant publications:**

Martin Schoeberl, Sahar Abbaspour, Benny Akesson, Neil Audsley, Raffaele Capasso, Jamie Garside, Kees Goossens, Sven Goossens, Scott Hansen, Reinhold Heckmann, Stefan Hepp, Benedikt Huber, Alexander Jordan, Evangelia Kasapaki, Jens Knoop, Yonghui Li, Daniel Prokesch, Wolfgang Puffitsch, Peter Puschner, Andre Rocha, Claudio Silva, Jens Sparso, and Alessandro Tocchi. **T-CREST: Time-predictable multi-core architecture for embedded systems.** *Journal of Systems Architecture*, 61(9):449-471, 2015. [pdf](http://www.jopdesign.com/doc/t-crest-jnl.pdf) [doi](http://dx.doi.org/10.1016/j.sysarc.2015.04.002)
