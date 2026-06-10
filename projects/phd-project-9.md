---
title: "PhD Project 9 (MDH)"
permalink: /projects/phd-project-9/
---

## Resource management for dependable industrial applications

This position has already been filled.

[Apply Now](http://www.mdh.se/hogskolan/jobb/lediga-jobb-1.103104?rmpage=job&rmjob=58&rmlang=UK "Apply Now")

- **Important**: don’t forget to mention in your application how you found out about the position.

**Host:** [Mälardalen University College (MDH)](/partners/mdh/), [School of Innovation, Design and Engineering](http://www.mdh.se/idt?l=en_UK).

- Main supervisor: [Dr. Moris Behnam](http://www.es.mdh.se/staff/157-Moris_Behnam), [moris.behnam@mdh.se](mailto:moris.behnam@mdh.se) (contact person)
- Co-supervisor: Assistant Prof. [Alessandro Papadopoulos](http://www.idt.mdh.se/~aps01/), alessandro.papadopoulos@mdh.se

**Requirements:**

- [Mandatory requirements for all PhD positions](/job-requirements/)
- **The following skills are also required:**
  - Programming skills
  - Operating systems
- **The following skills are considered to be merits:**
  - Experience with real-time systems
  - Knowledge of communication middleware
  - Knowledge of control theory and optimization
  - Knowledge of machine learning techniques
  - Experience with virtualization technologies

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

**References:**

[1] A. Iosup, S. Ostermann, M. N. Yigitbasi, R. Prodan, T. Fahringer, and D. Epema. “Performance Analysis of Cloud Computing Services for Many-Tasks Scientific Computing”. In: IEEE Transactions on Parallel and Distributed Systems 22.6 (2011), pp. 931–945. doi: 10.1109/TPDS.2011.66.

[2] H. P. Breivold and K. Sandstrom. “Internet of Things for Industrial Automation – Challenges and Tech- nical Solutions”. In: Proceedings of the 2015 IEEE International Conference on Data Science and Data Intensive Systems (DSDIS). DSDIS ’15. Washington, DC, USA: IEEE Computer Society, 2015, pp. 532– 539. doi: 10.1109/DSDIS.2015.11.

[3] Industrial internet consortium. Industrial Internet. url: <http://www.industrialinternetconsortium.org/>.

[4] Industrial Internet Insights Report for 2015. Tech. rep. Accenture, 2015.

[5] E. Borgia. “The Internet of Things vision: Key features, applications and open issues”. In: Computer Communications 54 (2014), pp. 1 –31. doi: 10.1016/j.comcom.2014.09.008.

[6] R. Drath and A. Horch. “Industrie 4.0: Hit or Hype? [Industry Forum]”. In: IEEE Industrial Electronics Magazine 8.2 (2014), pp. 56–58. doi: 10.1109/MIE.2014.2312079.

[7] Industrie 4.0. url: <http://www.plattform-i40.de/>.

[8] K. Sandström, A. Vulgarakis, M. Lindgren, and T. Nolte. “Virtualization technologies in embedded real- time systems”. In: 2013 IEEE 18th Conference on Emerging Technologies Factory Automation (ETFA). 2013, pp. 1–8. doi: 10.1109/ETFA.2013.6648012.

[9] M. Garcia-Valls, T. Cucinotta, and C. Lu. “Challenges in real-time virtualization and predictable cloud computing”. In: Journal of Systems Architecture 60.9 (2014), pp. 726 –740. doi: http://dx.doi.org/ 10.1016/j.sysarc.2014.07.004.

[10] A. V. Papadopoulos. “Design and Performance Guarantees in Cloud Computing: Challenges and Oppor- tunities”. In: 10th International Workshop on Feedback Computing. Seattle, WA, USA, 2015.

[11] B. Wittenmark, J. Nilsson, and M. Torngren. “Timing problems in real-time control systems”. In: Ameri- can Control Conference, Proceedings of the 1995. Vol. 3. 1995, 2000–2004 vol.3. doi: 10.1109/ACC.1995. 531240.

[12] A. Aminifar, S. Samii, P. Eles, Z. Peng, and A. Cervin. “Designing High-Quality Embedded Control Systems with Guaranteed Stability”. In: 2012 IEEE 33rd Real-Time Systems Symposium. 2012, pp. 283– 292. doi: 10.1109/RTSS.2012.79.

[13] A. V. Papadopoulos, M. Maggio, A. Leva, and E. Bini. “Hard Real-Time Guarantees in Feedback-based Resource Reservations”. In: Real-Time Systems 51.3 (2015), pp. 221–246. doi: 10.1007/s11241-015- 9224-1.

[14] P. D. Christofides, R. Scattolini, D. M. de la Pena, and J. Liu. “Distributed model predictive control: A tutorial review and future research directions”. In: Computers & Chemical Engineering 51 (2013). CPC VIII, pp. 21 –41. doi: http://dx.doi.org/10.1016/j.compchemeng.2012.05.011.

[15] P. Mhaskar. “Robust Model Predictive Control Design for Fault-Tolerant Control of Process Systems”. In: Industrial & Engineering Chemistry Research 45.25 (2006), pp. 8565–8574. doi: 10.1021/ie060237p.

[16] R. Scattolini. “Architectures for distributed and hierarchical Model Predictive Control – A review”. In: Journal of Process Control 19.5 (2009), pp. 723 –731. doi: http://dx.doi.org/10.1016/j.jprocont. 2009.02.003.

[17] Nebbiolo Technologies. Fog Computing: Keystone of Industry 4.0. url: <http://www.nebbiolo.tech/>.

[18] F. Bonomi, R. Milito, P. Natarajan, and J. Zhu. “Fog Computing: A Platform for Internet of Things and Analytics”. In: Big Data and Internet of Things: A Roadmap for Smart Environments. Ed. by N. Bessis and C. Dobre. Cham: Springer International Publishing, 2014, pp. 169–186. doi: 10.1007/978-3-319- 05029-4\_7.

[19] P. Leitao, A. W. Colombo, and S. Karnouskos. “Industrial Automation Based on Cyber-physical Systems Technologies”. In: Comput. Ind. 81.C (Sept. 2016), pp. 11–25. doi: 10.1016/j.compind.2015.08.004.

[20] I. Stojmenovic. “Fog computing: A cloud to the ground support for smart things and machine-to-machine networks”. In: 2014 Australasian Telecommunication Networks and Applications Conference (ATNAC). 2014, pp. 117–122. doi: 10.1109/ATNAC.2014.7020884.

[21] J. O. Kephart and D. M. Chess. “The vision of autonomic computing”. In: Computer 36.1 (2003), pp. 41– 50. doi: 10.1109/MC.2003.1160055.

[22] R. de Lemos et al. “Software Engineering for Self-Adaptive Systems: A Second Research Roadmap”. In: Software Engineering for Self-Adaptive Systems II: International Seminar, Dagstuhl Castle, Germany, October 24-29, 2010 Revised Selected and Invited Papers. Ed. by R. de Lemos, H. Giese, H. A. Muller, and M. Shaw. Berlin, Heidelberg: Springer Berlin Heidelberg, 2013, pp. 1–32. doi: 10.1007/978-3-642-35813-5\_1.

[23] M. Maggio, H. Hoffmann, A. V. Papadopoulos, J. Panerati, M. D. Santambrogio, A. Agarwal, and A. Leva. “Comparison of Decision-Making Strategies for Self-Optimization in Autonomic Computing Systems”. In: ACM Trans. Auton. Adapt. Syst. 7.4 (Dec. 2012), 36:1–36:32. doi: 10.1145/2382570.2382572.

[24] D. Zeidler, S. Frey, K.-L. Kompa, and M. Motzkus. “Evolutionary algorithms and their application to optimal control studies”. In: Phys. Rev. A 64 (2 2001), p. 023420. doi: 10.1103/PhysRevA.64.023420.
