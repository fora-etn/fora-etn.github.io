---
title: "ESR2"
permalink: /people/esr2/
---

## Alexandre Silva Venito

- **Education:**
  - M.Sc. in Computer Science, UFF – Universidade Federal Fluminese
  - B.Sc. in Electrical Engineering – CEFET-RJ
- **Research Interests:**
  - Real-Time Systems

![](/assets/uploads/2018/07/Venito.jpeg){:.esr-photo}

**Ressearch project status:**

**Ended in 2021**

## Resource separation mechanisms for Fog Nodes

**Host:** [Technische Universität Kaiserslautern (TUKL)](/partners/tukl/), [Chair of Real Time Systems](https://rts.eit.uni-kl.de/).

- Main supervisor: Prof. Gerhard Fohler, [fohler@eit.uni-kl.de](mailto:fohler@eit.uni-kl.de) (contact person)
- Co-supervisor: Rodrigo Coelho, coelho@eit.uni-kl.de

**Objectives:**

1. Ensure the temporal isolation of tasks and partitions on MCPs taking platform resource contentions into account.
2. Develop resource sharing mechanisms for managing access to shared resources such as bus and memory controller.

**Expected Results**:

- Runtime resource management technique controlling access to shared resources such as bus and memory controller, implemented as “scheduling servers”
- Prototype implementation and evaluation of time- and memory access scheduling servers, running on each core of a MCP
- Scheduling algorithm based on runtime mechanism for temporal isolation on multicore platforms, that finds a valid allocation of tasks to cores, task schedules and slot-level budget reservations for each server, such that the specified task set constraints (including deadlines) are met.

**Planned visits and collaboration:**

- SYSGO (Dr. Henrik Theiling): Training on multicore platforms and hypervisors; integration of servers in PikeOS
