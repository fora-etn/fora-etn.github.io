---
title: "PhD Project 8 (DTU)"
permalink: /projects/phd-project-8/
---

## Fog configuration for critical control applications

[Apply Now](http://www.dtu.dk/english/career/job?id=3b156222-8093-499b-adac-a4950d20a27d "Apply Now")

- **Important**: don’t forget to mention in your application how you found out about the position.

**Host:** [Technical University of Denmark (DTU)](/partners/dtu/), [Embedded Systems Engineering (ESE)](http://www.compute.dtu.dk/english/research/ESE) section.

- Main supervisor: Prof. Paul Pop, [paupo@dtu.dk](mailto:paupo@dtu.dk) (contact person)
- Co-supervisor: Prof. Jan Madsen, jama@dtu.dk

**Requirements:**

- [Mandatory requirements for all PhD positions](/job-requirements/)
- Master’s in Computer Science or equivalent
- Knowledge of algorithms and data structures
- Experience with developing large complex software
- Demonstrated ability to write technical reports, articles is a plus

**Objectives:**

1. Support the virtualisation of control needed for the IT/OT convergence
2. Develop methods and tools for the configuration of the Fog Computing Platform for critical control applications, such that they have the same level of service as on a dedicated OT infrastructure.

**Expected Results**:

- Evaluation and analysis report of the mechanisms introducing latencies and jitter that increase the worst-case delays in the network, and decrease the dependability
- Methods and tools for the configuration of Fog Nodes and for the configuration of TSN switches
- Analysis and optimization algorithms to maximise the QoC
- Evaluation and integration of the methods and tools with TTTech’s tool flows.

**Planned visits and collaboration:**

- TTTech (Dr. Silviu S. Craciunas): Formulate the optimization problems needed for the configuration and define the interfaces to TTTech’s tools;
- Danish Technological Institute (Dr. Lars Dalgaard): Use the developed tools to configure virtual PLCs for a robotic use case.

**Description:**

Many application areas have traditionally implemented their systems using a “federated architecture”, where each node implements one function, and the nodes are interconnected using dedicated communication links. This has led to overprovisioning, increasing the number of nodes, and the associated wiring, cost and SWaP, i.e., size, weight and power. The current trend, even in highly-critical areas such as avionics, is towards “integrated architectures” [[1]](#_ftn1), where several mixed-criticality functions share the same node and multiple types of traffic converge onto the same communication infrastructure. The same trend is currently impacting industrial automation systems, where we see the IT and OT convergence [[2]](#_ftn2). A disadvantage of integrated architectures is the complexity increase of the system: new possible interactions will arise among applications of different criticality implemented on the same platform. The solution is to demonstrate that applications of different criticality levels are separated, so they cannot influence each other. This separation is achieved via “partitioning”, which “fault containment equivalent to an idealised system in which each partition is allocated an independent processor and associated peripherals and all inter-partition communications are carried on dedicated lines [[3]](#_ftn3)”. Partitioning has two dimensions: *spatial* and *temporal*. Spatial partitioning ensures that an application in a partition will not interfere with the code and data of another partition. Temporal partitioning ensures that an application’s scheduled access to shared resources (e.g., processor or communication bus), cannot be affected by an application in another partition. The Fog Nodes implement such partitioning mechanisms. The separation at the communication level is achieved by TSN. When industrial control applications share the same architecture, there is the risk that the resource sharing jeopardises the stability of the control applications, due to the complex timing behaviours [[4]](#_ftn4) (called anomalies [[5]](#_ftn5)). Instability in control may lead to dangerous failures that can harm human life or the environment. Recent research in the real-time systems area has proposed resource management and configuration approaches such that the quality-of-control (QoC) is guaranteed [[6]](#_ftn6). The focus has been on determining a limited static configuration deciding, for example, the periods and priorities of tasks and their schedules. None of the current approaches can tackle Fog-based architectures that use virtualization and TSN-based communication. The resource management approaches in Cloud computing do not address non-functional properties as required by hard real-time control applications (e.g., deadlines), and resource management in real-time and safety critical systems ignore the QoC [[7]](#_ftn7).

**The innovation consists of tools and mechanisms to configure the Fog-based IT infrastructure such that the non-functional properties of robotics and industrial control applications are guaranteed. This will allow the virtualization of control, which is converges OT and IT for Industry 4.0**

In the proposed Fog infrastructure, the control applications are virtualized running as tasks on the Fog nodes and using TSN for communication. The goal is to configure the Fog infrastructure (where IT and OT are converged) to provide the same guarantees as the existing OT infrastructure. The objective of the project is to develop methods and tools for the configuration of the Fog-based infrastructure, such that the demanding hard real-time control algorithms at the device-level meet their stringent timing requirements (millisecond latencies and microsecond jitter) are satisfied and their QoC is satisfied, i.e., the stability of control is guaranteed. To guarantee these demanding requirements, we create system-level schedules for all the tasks and messages implementing a control algorithm. We assume that the Fog nodes are synchronized, which can be achieved by the clock synchronization in TSN, the tasks are scheduled using schedule tables inside partitions, and the critical partitions are also statically scheduled, similar to the ARINC 653 standard in avionics, which is supported by partitioned OSes such as PikeOS from SYSGO. The communication is mapped to the “time sensitive” traffic class of TSN, which uses high-priority queues that are scheduled using Gate Control Lists (GCLs). We have shown how partitions and schedules can be configured to guarantee deadlines for hard real-time applications [[8]](#_ftn8), and we have proposed configuration approaches for TTEthernet [[9]](#_ftn9) and TSN [[10]](#_ftn10). We have also shown how tasks and messages can be scheduled jointly [[11]](#_ftn11). The focus of this project is on the configuration of the Fog infrastructure to guarantee QoC of the virtualized control, which has not been investigated. The methods and tools have to determine at the computation-level: the mapping of tasks to processing elements, the assignment of tasks to partitions, the scheduling of the critical partitions, and and the schedule tables for all tasks. At the communication level (TSN) we are interested to determine the routing of the traffic flows, the assignment of the flows to queues and the GCLs for the time sensitive traffic. This has to be done not only to provide the guarantees for the control tasks, but also to leave resources available to the non-critical tasks maximizing their QoS. Such optimization problems in even simpler contexts have been shown to be NP-complete, so we will implement heuristic algorithms that can produce good solutions in a short time. This project will collaborate with the other PhD students working on “Resource Management” for Fog to integrate these methods and algorithms into the overall Fog provisioning and orchestration framework. In addition, part of the configuration may be done at runtime. The runtime reconfiguration is needed to adapt to a new environment, to recover from failure, or to recover from a security attack. The online runtime reconfiguration has to be fast and still provide guarantees for the industrial control applications.

[[1]](#_ftnref1) ARINC 653P0: Avionics Application Software Standard Interface, Part 0, Overview of ARINC 653. ARINC (Aeronautical Radio, Inc), 2013.

[[2]](#_ftnref2) https://www.tttech.com/news-events/newsroom/details/the-automation-pyramid/

[[3]](#_ftnref3) John Rushby. Partitioning for avionics architectures: Requirements, mechanisms, and assurance. NASA Contractor Report CR-1999-209347, NASA Langley Research Center, June 1999.

[[4]](#_ftnref4) Anton Cervin, “Integrated control and real-time scheduling.” PhD dissertation, Lund University, 2003.

[[5]](#_ftnref5) A. Aminifar, P. Eles, Z. Peng, and A. Cervin, “Stability- aware analysis and design of embedded control systems,” in Proceedings of the 11th

[[6]](#_ftnref6) Årzén, K. E., Cervin, A., & Henriksson, D. (2003). Resource-constrained embedded control systems: Possibilities and research issues. In Proceedings of CERTS’03–Co-Design of Embedded Real-Time Systems Workshop.

[[7]](#_ftnref7) García-Valls, M., Cucinotta, T. and Lu, C., 2014. Challenges in real-time virtualization and predictable cloud computing. Journal of Systems Architecture, 60(9), pp.726-740.

[[8]](#_ftnref8) Tămaş-Selicean, D., & Pop, P. (2015). Design optimization of mixed-criticality real-time embedded systems. ACM Transactions on Embedded Computing Systems (TECS), 14(3), 50.

[[9]](#_ftnref9) Tămaş–Selicean, D., Pop, P., & Steiner, W. (2015). Design optimization of TTEthernet-based distributed real-time systems. Real-Time Systems, 51(1), 1-35.

[[10]](#_ftnref10) Craciunas, Silviu S., e`t al. “Scheduling Real-Time Communication in IEEE 802.1 Qbv Time Sensitive Networks.” Proceedings of the 24th International Conference on Real-Time Networks and Systems. ACM, 2016.

[[11]](#_ftnref11) Craciunas, S. S., & Oliver, R. S. (2016). Combined task-and network-level scheduling for distributed time-triggered systems. Real-Time Systems, 52(2), 161-200.

**Relevant publications:**

Please see the following publications for an indication of the type of papers that we write in this area (the PDFs can be downloaded from [here](http://www2.compute.dtu.dk/~paupo/publications.html)).

[**Design Optimization of Cyber-Physical Distributed Systems using IEEE Time-sensitive Networks (TSN).**](http://orbit.dtu.dk/en/publications/design-optimization-of-cyberphysical-distributed-systems-using-ieee-timesensitive-networks-tsn(3211c8f6-c154-490a-ae68-3c946f89afec).html) / [Pop, Paul](http://orbit.dtu.dk/en/persons/paul-pop(9ae8b873-7735-48b5-8b97-9fedf1891f0f).html); Lander Raagaard, Michael; Craciunas, Silviu S. ; Steiner, Wilfried. In: [IET Cyber-Physical Systems: Theory and Applications](http://orbit.dtu.dk/en/journals/iet-cyberphysical-systems-theory-and-applications(28ec2240-8643-486e-977d-a43a0b9042ab).html), Vol. 1, No. 1, 2016, p. 86-94.

[**Design Optimization of Mixed-Criticality Real-Time Embedded Systems.**](http://orbit.dtu.dk/en/publications/design-optimization-of-mixedcriticality-realtime-embedded-systems(2100c01f-02f2-468b-86d1-423c8ad8099f).html) / [Tamas-Selicean, Domitian](http://orbit.dtu.dk/en/persons/domitian-tamasselicean(352ae100-7dba-4ea1-885c-f08c262525ed).html)[; Pop, Paul](http://orbit.dtu.dk/en/persons/paul-pop(9ae8b873-7735-48b5-8b97-9fedf1891f0f).html). In: [ACM Transactions on Embedded Computing Systems](http://orbit.dtu.dk/en/journals/a-c-m-transactions-on-embedded-computing-systems(15bd1ec9-0868-4161-8308-f49bdce3d440).html), Vol. 14, No. 3, 50, 2015.

[**Design optimization of TTEthernet-based distributed real-time systems.**](http://orbit.dtu.dk/en/publications/design-optimization-of-ttethernetbased-distributed-realtime-systems(421b1f95-2577-4485-98d9-234be06bdbb1).html) / [Tamas-Selicean, Domitian](http://orbit.dtu.dk/en/persons/domitian-tamasselicean(352ae100-7dba-4ea1-885c-f08c262525ed).html)[; Pop, Paul](http://orbit.dtu.dk/en/persons/paul-pop(9ae8b873-7735-48b5-8b97-9fedf1891f0f).html); Steiner, Wilfried. In: [Real-Time Systems](http://orbit.dtu.dk/en/journals/realtime-systems(e1619c69-1b5f-4e5a-a8d4-26d5ef2257ad).html), Vol. 51, No. 1, 2015, p. 1-35.
