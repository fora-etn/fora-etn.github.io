---
title: "ESR5"
permalink: /people/esr5/
---

## Zeinab Bakhshi

- **Education:**
  - M.Sc. degree in Computer System Architecture from Islamic Azad University
  - B.Sc. degree in computer Hardware engineering
- **Research Interests:**
  - Cyber physical systems,
  - Security, Safety, Networking, Error Detection,
  - Error Recovery and Fault Removal,
  - Fog Computing, Embedded Systems,
  - Industrial Automation

![](/assets/uploads/2018/07/Zeinab_Bakhshi_IDT_DSC3135.jpg){:.esr-photo}

**Research project status:**

**Ongoing**

PhD Student

*[zeinab.bakhshi@mdh.se](mailto:zeinab.bakhshi@mdh.se)*

## Dependability Services for Fog Computing Infrastructure

**Host:** [Mälardalen University College (MDH)](/partners/mdh/), [School of Innovation, Design and Engineering](http://www.mdh.se/idt?l=en_UK).

- Main supervisor: Prof. Hans Hansson, [hans.hansson@mdh.se](mailto:hans.hansson@mdh.se) (contact person)
- Co-supervisor: Prof. Sasikumar Punnekkat, [sasikumar.punnekkat@mdh.se](mailto:sasikumar.punnekkat@mdh.se)
- Co-supervisor: Dr. Guillermo Rodriguez-Navas, [guillermo.rodriguez-navas@mdh.se](mailto:guillermo.rodriguez-navas@mdh.se)

**Objectives:**

1. Specification and design of dynamic and adaptive dependability services for Fog Computing in robotics and factory automation.
2. Developing mechanisms for error detection, error recovery, and fault diagnosis and removal, including recovery algorithms.

**Expected Results**:

- Specification of dependability attributes for Fog Computing.
- Dependability framework for Fog Computing, including adequate system partitioning and subsystem design.
- Infrastructure-level dependability service prototypes: mechanisms for redundancy, error detection, failure recovery, fault diagnosis and fault removal.
- Demonstration and analysis of nearly concurrent fault manifestations and multiple overlapping faults.

**Visits and collaboration:**

- TTTech (Dr. Wilfried Steiner): Gather dependability requirements and formulate dependability metrics & patterns.

## Licentiate Dissertation

**Title:** **Persistent and Fault-Tolerant Storage at the Fog Layer**

**Defense Date: 14th October 2021**

**Abstract:**

Clouds are powerful computer centers that provide computing and storage facilities that can be remotely accessed. The flexibility and cost-efficiency offered by clouds have made them very popular for business and web applications. The use of clouds is now being extended to safety-critical applications such as factories. However, cloud services do not provide time predictability which creates a hassle for such time-sensitive applications. Moreover, delays in the data communication between clouds and the devices the clouds control are unpredictable. Therefore, to increase predictability, an intermediate layer between devices and the cloud is introduced. This layer, the Fog layer, aims to provide computational resources closer to the edge of the network. However, the fog computing paradigm relies on resource-constrained nodes, creating new potential challenges in resource management, scalability, and reliability.  
Solutions such as lightweight virtualization technologies can be leveraged for solving the dichotomy between performance and reliability in fog computing. In this context, container-based virtualization is a key technology providing lightweight virtualization for cloud computing that can be applied in fog computing as well. Such container-based technologies provide fault tolerance mechanisms that improve the reliability and availability of application execution.  
By the study of a robotic use-case, we have realized that persistent data storage for stateful applications at the fog layer is particularly important. In addition, we identified the need to enhance the current container orchestration solution to fit fog applications executing in container-based architectures.  
In this thesis, we identify open challenges in achieving dependable fog platforms. Among these, we focus particularly on scalable, lightweight virtualization, auto-recovery, and re-integration solutions after failures in fog applications and nodes. We implement a testbed to deploy our use-case on a container-based fog platform and investigate the fulfillment of key dependability requirements. We enhance the architecture and identify the lack of persistent storage for stateful applications as an important impediment for the execution of control applications. We propose a solution for persistent fault-tolerant storage at the fog layer, which dissociates storage from applications to reduce application load and separates the concern of distributed storage. Our solution includes a replicated data structure supported by a consensus protocol that ensures distributed data consistency and fault tolerance in case of node failures. Finally, we use the UPPAAL verification tool to model and verify the fault tolerance and consistency of our solution.
