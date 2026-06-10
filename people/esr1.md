---
title: "ESR1"
permalink: /people/esr1/
---

## Jan Ruh

#### Education:

- M.Sc. in Computer Science, Karlsruhe Institute of Technology, KIT, Germany

#### Research Interests:

- Virtualization of real-time systems
- Focus on virtualization of time-triggered systems

![](/assets/uploads/2018/07/ESR1.jpg){:.esr-photo}

**Ressearch project status:**

**Ongoing**

PhD Student

TTTech

jan.ruh@tttech.com

*Supervisors: Dr. Wilfried Steiner (wilfried.steiner@tttech.com) Prof. Dipl.-Ing. Dr. Gerhard Fohler*

## Deterministic Virtualization for Mixed Criticality Industrial Applications

In Fog Computing, virtualization and time sensitive networking (TSN) are commonly accepted and presumed to act as key enabler of IIoT. TSN provides deterministic networking, whereas virtualization provides scalability, availability, reliability, and security. Network function virtualization (NFV) is a popular example of how virtualization can facilitate novel technologies. In case of NFV, a hypervisor today already enables the consolidation of multiple virtual network functions (VNF) on a commercial off-the-shelf multicore processor, effectively reducing operating expenses (OPEX), capital expenses (CAPEX), and time-to-value (TTV) for telecommunication service providers.

Virtualization could help manufacturing and producing industry to reduce their OPEX, CAPEX, and TTV as well, since hypervisors running on COTS MCPs enable novel use cases, such as control as a service (CaaS), dynamic configuration of production sites, and online optimization of production processes. However, for many use cases virtualization must meet additional, demanding non-functional requirements.

**Objectives & Expected Results:**

- Time-triggered hypervisor prototype: Development of a hypervisor prototype that allows for the execution of time-triggered hard real-time applications inside VMs while allowing dynamic management of best-effort VMs.
  - This includes clock synchronization of the hypervisor and its VMs to enable dispatching of virtual CPUs according to a global computation and communication schedule
  - Minimizing interference between co-located virtual CPUs by means of memory bandwidth servers and cache partitioning
- Provision of formal methods:
  - Provide a bound on the achievable clock synchronization precision since the clock synchronization precision is an important parameters in schedule generation
  - Provide formal methods to show the timeliness of the time-triggered hypervisor’s execution of a schedule given a worst-case response time analysis.

#### Publications

- [“The Need for Deterministic Virtualization in the Industrial Internet of Things”](https://dl.acm.org/citation.cfm?id=3313222) — Jan Ruh, Wilfried Steiner, IoT-Fog ’19 Proceedings of the Workshop on Fog Computing
- “[Towards Consolidating Industrial Use Cases on a Common Fog Computing Platform](https://ieeexplore.ieee.org/abstract/document/9211885/)” — Patrick Denzler, Jan Ruh, Marine Kadar, Cosmin Avasalcai, Wolfgang Kastner, 2020 25th IEEE International Conference on Emerging Technologies and Factory Automation (ETFA)
- “[The FORA Fog Computing Platform for Industrial IoT](https://arxiv.org/abs/2007.02696)” — Paul Pop, Bahram Zarrin, Mohammadreza Barzegaran, Stefan Schulte, Sasikumar Punnekkat, Jan Ruh, Wilfried Steiner, arXiv preprint arXiv:2007.02696
- “[Clock Synchronization in Virtualized Distributed Real-Time Systems Using IEEE 802.1AS and ACRN](https://ieeexplore.ieee.org/document/9530651)” — Jan Ruh, Wilfried Steiner, Gerhard Fohler, in IEEE Access, vol. 9, 2021
