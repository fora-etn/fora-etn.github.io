---
title: "ESR3"
permalink: /people/esr3/
---

## Eleftherios Kyriakakis

- **Education:**
  - PhD in Computer Science, DTU, Denmark
  - MSc in Information and Communication Technology, Embedded Systems, KTH, Sweden
  - BSc in Informatics and Computer Technology, TEI Lamia, Greece
- **Research Interests:**
  - Embedded Systems Design
  - Computer Architecture
  - Real-time & Fault-tolerant systems

![](/assets/uploads/2018/07/ESR3.jpg){:.esr-photo}

**Ressearch project status:**

**Ended in 2021**

*elky@dtu.dk*

[LinkedIn](https://www.linkedin.com/in/eleftherios-kyriakakis-48a7973b/)

## Open source Fog Node: hardware support for virtualization

**Host:** [Technical University of Denmark (DTU)](/partners/dtu/), [Embedded Systems Engineering (ESE)](http://www.compute.dtu.dk/english/research/ESE) section.

- Main supervisor: Prof. Martin Schoeberl, [masca@dtu.dk](mailto:masca@dtu.dk) (contact person)
- Co-supervisor: Prof. Jens Sparsø, jspa@dtu.dk

**Objectives:**

1. Investigate clock synchronization in time-aware Ethernet networks and develop the necessary hardware/software mechanisms to support nanosecond precision clock synchronization.
2. Investigate distributed task schedule execution in time-aware Ethernet networks and develop the necessary software stacks to allow for synchronized distributed task execution.
3. Integrate the developped mechanisms with common industrial Ethernet protocols and analyze their performance
4. Develop and evaluate time-predictable hardware mechanisms to support virtualization, such as time-predictable virtual memory and time-predictable virtualization of I/O

**Description:**

Current multicore processors found in off-the-shelf Fog Computing end-systems are optimized for average-case performance and hardly time-predictable.  
Hardware/software mechanisms have to be integrated in the application layer as well as in the communication layer to allow for time-predictable application execution and communication latency. Furthermore, Fog Computing implies virtualization but common techniques such as paging and address translation caching with a TLB are hardly time-predictable and have to be rethought. Within this PhD project, time-predictable hardware mechanisms and software stacks will be developed and WCET analyzed to support real-time task execution and communication guarantees for Fog Computing.  
The project will extend the [T-CREST platform](https://github.com/t-crest).

**Internship and collaboration:**

- TTTech (Wilfried Steiner)

**Thesis defence:**

![](/assets/uploads/2018/07/Screen-Shot-2021-06-29-at-15.12.13.png) ![](/assets/uploads/2018/07/Screen-Shot-2021-06-29-at-15.13.05.png)

[PhD Thesis Presentation](/assets/uploads/2018/07/ESR3_PhD_Thesis_Presentation.pptx)

**Publications:**

1. [A time-predictable open-source TTEthernet end-system](https://orbit.dtu.dk/en/publications/a-time-predictable-open-source-ttethernet-end-system). Kyriakakis, E., Lund, M., Pezzarossa, L., Sparsø, J. & Schoeberl, M., Sep 2020, In : Journal of Systems Architecture. 108, 10 p., 101744.
2. [Implementing time-triggered communication over a standard ethernet switch](https://orbit.dtu.dk/en/publications/implementing-time-triggered-communication-over-a-standard-etherne). Kyriakakis, E., Sparsø, J. & Schoeberl, M., 2019, *Proceedings of the Fog-IoT Workshop 2019.* G. S. R. & J. O. (eds.). [Association for Computing Machinery](https://orbit.dtu.dk/en/persons/eleftherios-kyriakakis/publications/#), p. 21-25 5 p.
3. [InterNoC: Uniﬁed Deterministic Communication For Distributed NoC-based Many-Core](https://orbit.dtu.dk/en/publications/internoc-uni%EF%AC%81ed-deterministic-communication-for-distributed-noc-b). Kyriakakis, E., Sparsø, J. & Schoeberl, M., 2019, *Proceedings of the 13th Junior Researcher Workshop on Real-Time Computing.* p. 29-32.
4. [Hardware assisted clock synchronization with the IEEE 1588-2008 precision time protocol](https://orbit.dtu.dk/en/publications/hardware-assisted-clock-synchronization-with-the-ieee-1588-2008-p). Kyriakakis, E., Sparsø, J. & Schoeberl, M., 2018, *Proceedings of the 26th International Conference on Real-Time Networks and Systems, RTNS 2018.* Association for Computing Machinery, p. 51-60 10 p.
