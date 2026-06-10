---
title: "ESR9"
permalink: /people/esr9/
---

## Václav Struhár

- **Education:**
  - - MSc. Software Engineering, Mälardalen University, Sweden
    - BSc. Informatics, University of West Bohemia, Czech republic
- **Research Interests:**
  - Artificial Intelligence, Discrete optimization

![](/assets/uploads/2018/07/ESR9.jpg){:.esr-photo}

**Research project status:**

**Ongoing**

PhD Student

*vaclav.struhar@mdh.se*

## Resource management for dependable industrial applications

**Host:** [Mälardalen University College (MDH)](/partners/mdh/), [School of Innovation, Design and Engineering](http://www.mdh.se/idt?l=en_UK).

- Main supervisor: [Dr. Moris Behnam](http://www.es.mdh.se/staff/157-Moris_Behnam), [moris.behnam@mdh.se](mailto:moris.behnam@mdh.se) (contact person)
- Co-supervisor: Assistant Prof. [Alessandro Papadopoulos](http://www.idt.mdh.se/~aps01/), alessandro.papadopoulos@mdh.se

**Objectives:**

1. Design a middleware that manages requests and local resources to provide more predictable service through the Fog and Cloud to the automation devices.
2. Develop runtime resource management mechanisms, such that hard real-time apps meet their constraints and QoS is maximized.

**Expected Results**:

- The design of resource management functionality capable of dynamically allocating resources spanning the complete continuum from Fog to Cloud, focused on hard real-time applications.
- Implement resource management algorithms, using approaches from control theory and machine learning; guaranteeing highly critical tasks while using spare capacity for the lower critical ones.
- Validate the correctness of the solutions by using simulations and implementations.
- Develop use cases from the automation application domains, jointly with ABB and DANFOSS.

**Planned visits and collaboration:**

- TU Wien  (Assistant Prof. Stefan Schulte): Define jointly with TU Wien and TTTech runtime resource management optimization problems
- VCE (Dr. Peter Wallin): Evaluate the runtime resource management mechanisms on the VCE use case.

**Overview:**

Current cloud and IoT architectures provide potentially enabling technologies for the ubiquitous adoption in industrial automation applications, but we are still far from solutions providing predictable and dependable computational performance [1, 2]. Industrial internet uses sensors, software, machine-to-machine collaboration and various technologies to gather and analyze data from physical and virtual world for optimized operations and providing services [3]. IoT can be a potential value creator in industrial automation [4], through the combination of advanced data analytics and internet of things to connect machines, computers and people to enable intelligent industrial operations in many industries, such as industrial domain, smart city domain, and health well-being domain [5]. In particular, IoT combined with cloud technologies are the enabling technologies for Industry 4.0 [6, 7, 8]. Cloud services should, in fact, extend the functionalities of current industrial devices, creating interconnected smart industrial devices and services with predictable performance.

On the other hand, cloud technologies pose diverse challenges at the architectural level, such as providing predictable performance in terms of Quality of Service (QoS), and dependability [9, 10]. More specifically, timing is of utter importance when dealing with industrial automation, where controllers must be executed periodically with possibly hard real-time constraints [11, 12, 13]. Furthermore, when dealing with highly critical controllers, guaranteeing only timing properties might not be sufficient, and this calls for redundant architectures [14, 15]. In general, there is a number of different control applications that ranges from highly critical, that must meet their deadlines, redundancy is required, and a given level of Quality of Control (QoC) must be achieved, up to lower critical applications where best-effort approaches are sufficient for their operation, and they should be properly designed and coordinated [16].

In such a scenario, fog devices can play also a major role, in providing more predictable and reliable guar- antees for the correct operation of industrial applications. Fog architectures will enable a powerful convergence, unification and standardization at the networking, security, data, computing, and control levels. It will lead to improved interoperability, security, more efficient and rich control, and higher manufacturing efficiency and flexibility [17, 18, 19, 20].

**Description:**

In this project, the objective is to design a fog middleware that manages requests and local resources to provide more predictable service through the cloud to the automation devices.

Such a middleware should manage and coordinate highly critical control loops to guarantee that their timing performance, as well as their QoS, are achieved and kept within specified limits. The management is enacted through efficient allocation of resources, possibly over-provisioning computational capacity for highly critical tasks while using spare capacity only for the lower critical ones. A first key challenge is to provide methodologies that can be executed at runtime in order to decide how to allocate the resources to the different control applications.

The fundamental contribution of the PhD project proposal is to investigate and design resource allocation middleware policies for providing predictable performance of Fog devices. The solutions will be sought in different fields, with a particular attention to control theory and machine learning, since these look the most promising approaches for dealing with autonomic solutions in cloud [21, 22, 23]. In particular, resource allocation problems can be cast in optimization problems that can be solved through optimal control strategies – i.e., control techniques that base their actions based on the solution of an optimization problem that is solved iteratively at runtime –, genetic algorithms or a combination thereof [24]. More specifically, Multiple Inputs Multiple Outputs (MIMO) Model Predictive Control (MPC) strategies [14, 15] seem to be the most promising solution in this direction, since control theoretical tools will allow us to provide guarantees on the obtainable performance at runtime, while optimizing the resource utilization. In order to validate the correctness of the solutions that will be developed within this project, we are planning to use both simulations and, in a later stage, real implementations.

**Publications:**

For a complete list of publications please visit the following page: [Publication Page](https://scholar.google.com/citations?user=JECA0ccAAAAJ&hl=en)
