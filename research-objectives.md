---
title: "Research objectives"
permalink: /research-objectives/
---

#### FORA’s Research

Industries are digitalized. The machines are talking. This will bring a net value of USD 1.7 trillion by 2020 worldwide. We need to bring Cloud Computing and Data Analytics closer to the machines, we need to develop an open Fog Computing Platform. Fog Computing, also sometimes called Edge Computing, brings the Cloud “closer to the ground”, to the edge of the network.

**What is Fog Computing?**

**What are the benefits when machines are talking?**

The **FORA** **research objectives** focused on: future industrial automation architectures and applications based on Fog Computing, deterministic virtualization and execution, deterministic wired and wireless communication, resource provisioning and resource management, Service-Oriented Architecture (SOA), real-time data analytics and security. The result was an **open architecture** built on open source and open standards, e.g., Time-Sensitive Networking (TSN), OPC Unified Architecture (UA) and 5G.

The research happened at the intersection of several research areas: Cloud Computing and Software Engineering, Industrial Automation and Real-Time Systems, and Machine Learning, Security and Safety.

![](/assets/uploads/2017/10/FORA-research-areas.png)

#### Motivation

Although Europe has been undergoing a process of deindustrialization, 80% of its exports come from manufacturing, which is responsible for 33 million jobs [[1]](#_ftn1). The European Commission has set a 2020 target that 20% of value added should come from manufacturing [[2]](#_ftn2). Therefore, member states are creating initiatives such as Industry 4.0 [[3]](#_ftn3) in Germany, Factory of the Future in France and Italy and “Catapult centres” in the UK, in order to strengthen the digital industrialization within Europe [[4]](#_ftn4). We are at the beginning of a new industrial revolution (we will use the term **Industry 4.0**), which will bring increased productivity and flexibility, mass customization, reduced time-to-market, improved product quality, innovations and new business models [[5]](#_ftn5). This will lead to [[6]](#_ftn6): 5% overall productivity increase (up to 55% in technical professions); 20-25% increase in production volume; 20-50% reduction in time-to-market; 10-40% reduction of maintenance costs, with 30-50% reduction of machine downtime. The Industrial Internet worldwide cumulative net value will be USD 1.7 trillion by 2020 worldwide [[7]](#_ftn7); this digital transformation [[8]](#_ftn8) will affect all industries.

However, Industry 4.0 will only become a reality through the **convergence** [[9]](#_ftn9) of **Operational** and **Information Technologies** (**OT** & **IT**), which are currently separated in a *hierarchical* *pyramid* (Purdue Reference Model [[10]](#_ftn10), PRM1 to PRM4, see fig. 1) and use different computation and communication technologies. OT consists of cyber-physical systems that monitor and control physical processes that manage, e.g., automated manufacturing, critical infrastructures, smart buildings and smart cities. These application areas are typically safety-critical and real-time (RT), requiring guaranteed extra-functional properties, such as, RT behavior, reliability, availability, industry-specific safety standards, and security. OT uses proprietary solutions implemented with barriers between each level, imposing severe restrictions on the information flow. Although IT such as Cloud Computing and Service Oriented Architecture (SOA) are used in the upper levels of the hierarchy, these cannot be applied to the bottom levels where very stringent extra-functional properties have to be guaranteed [[11]](#_ftn11). The convergence of IT and OT will be supported by: the increased usage of IP-protocols, e.g., standardized Deterministic Ethernet solutions from **IEEE Time-Sensitive Networking** (TSN) [[12]](#_ftn12) Task Group, upcoming 5G wireless standards [[13]](#_ftn13), and interoperability standards such as OPC Unified Architecture (**OPC UA**) [[14]](#_ftn14), all integrated into a **Fog Computing** [[15]](#_ftn15) platform, which brings computation, communication and storage closer to the edge of the network.

The **Fo**g Computing for **R**obotics and Industrial **A**utomation **(FORA) ETN was needed to achieve this convergence and cross the IT-OT gap**. We need to train **interdisciplinary** scientists that understand both the IT and OT domains, understand the needs of the industry (**intersectoral**), including SMEs, and that can have an impact at European-level (**international**). Such skills are currently lacking: The Industry 4.0 study of the European Parliament [[16]](#_ftn16), mentions that “*a very wide range of skills is required for [Industry 4.0] implementation. […] the convergence of IT, manufacturing, automation technology and software requires the development of a fundamentally new approach to training IT experts.*” **FORA** built an international, intersectoral and multidisciplinary network to train 15 Early-Stage Researchers (ESRs) in **Fog Computing** technologies to deliver **Industrial Automation** solutions. Fog Computing is a logical extension from Cloud Computing towards the edge of the network (where machines are located), enabling applications that demand guarantees in safety, security, and RT behavior [[17]](#_ftn17). FORA provided the ESRs with the scientific and transferable skills necessary for thriving careers, by a unique combination of “hands-on” research training, industry placements and courses and workshops on scientific and complementary soft skills.

#### 

#### Work Packages and PhD projects

The research objectives were organised in 3 research Work Packages and 15 PhD projects, see the diagram below.

![](/assets/uploads/2017/09/FORA-overview.png)

#### State-of the-art and potential of Fog Computing

**Fog Computing Platform.** Today’s industrial automation and robotics systems use proprietary OT organized in a hierarchical automation pyramid, which cannot support Industry 4.09. Information technology, such as Cloud Computing (CC) has gained significant popularity and we use Cloud-based services on a daily basis as a commodity. However, CC cannot provide dependability or Quality-of-Service (QoS) guarantees, so it cannot be used for industrial applications. Instead, a new paradigm, called **Fog Computing,** is needed as an architectural means to realize the IT/OT convergence17, [[18]](#_ftn18), [[19]](#_ftn19). Fog Computing (FC) is a “*system-level architecture that distributes resources and services of computing, storage, control and networking anywhere along the continuum from Cloud to Things*” [[20]](#_ftn20). Companies have started to bring computing and storage closer to the edge of the network (called Edge Computing), e.g., GE’s Predix [[21]](#_ftn21), CISCO’s IOx [[22]](#_ftn22), Nebbiolo’s solution branded by TTT as Nerve [[23]](#_ftn23). However, Edge Computing does not provide RT guarantees, nor considers OT (e.g., it cannot virtualize control and it is not hardened for dependability).

With FC, communication devices, such as switches and routers are extended with computational and storage resources to enable a variety of communication and computation options. FC will enable a powerful convergence, unification and standardization at the networking, security, data, computing, and control levels [[24]](#_ftn24), [[25]](#_ftn25). It will lead to improved interoperability, security, more efficient and rich control, and higher manufacturing efficiency and flexibility. The integration of computational resources and storage into the communication devices is realized in the **Fog Node (FN)**, but the design of a FN is a complex design engineering challenge. In recent years, multicores have been increasingly seen as a viable alternative to consolidate into one single platform several software functions. Multicores Processors (MCPs) can improve SWaP (Size, Weight & Power Reduction) and performance, allowing the integration of multiple applications to support IT and OT convergence, but introduce resource contentions due to sharing of hardware resources [[26]](#_ftn26) such as, cores, on-chip network, memory sub-system, etc. These shared resources result in dependencies leading to non-determinism [[27]](#_ftn27). This behavior is unacceptable in safety-critical hard Real-Time Systems (RTS), such as those in industrial automation, since failure may lead to damage to human life or the environment. Current approaches use **overprovisioning** (dedicated hardware for each function, shutting down all but one core in multicores), which is economically wasteful and impairs interoperability. When mixed-criticality functions share the same MCP, they are separated in different virtual machines (partitions) enforced using hardware-supported virtualization [[28]](#_ftn28), based on hypervisors. Commercial of-the-shelf (COTS) MCPs are designed for fast *average-case* performance, and current hypervisors (e.g., PikeOS from SYSGO) have to make pessimistic assumptions and use static partitions to support critical applications, which require predictable behavior even in the *worst-case*. This wastes system capacity which is akin to overprovisioning17. We need **deterministic** virtualization, i.e., which can guarantee the correctness of *non-functional properties* even in the worst-case. Virtualization should also support dynamic partitions, to allow non-critical applications to share the same MCP with critical applications. *Deterministic communication*, on the other hand, allows to increase the spatial distance between the physical process and the FN that controls it. Thus, control functions can be executed remotely on the FN. However, current communication solutions such as TSN have to be further extended to support deterministic communication and the convergence of IT and OT17. Industrial applications require *dynamic reconfiguration* to meet new business demands, allowing computation and communication services to evolve over time with minimal disruption. Regarding wireless, to enable ultra-reliable communication and low end-to-end latencies needed in critical applications, wireless communication must overcome dependability and latency challenges [[29]](#_ftn29).

***We need research*** to design a Fog Node, which consists of both hardware and Operating System (OS) mechanisms as well as communication protocols, based on deterministic virtualization and networking, that can address the stringent needs of the OT applications. Fog devices will provide more predictable and reliable guarantees for the correct operation of industrial applications.

**Provisioning and resource management.** In many applications, including industrial automation and robotics, several layers of Fog Nodes with differing computation, communication and storage capabilities will evolve, from powerful high-end FNs to low-end FNs with limited resources. A high-end FN per production site as external interface to other sites and the Cloud will allow control tasks to be implemented side by side with sophisticated data analytics, where the controls can run in a dedicated RT guest OS, while the data analytics run in a rich guest OS, e.g., Linux. Low-end FNs may be implemented within each machine or robot. Timing is critical in industrial automation, where controllers must be executed periodically with hard RT constraints [[30]](#_ftn30), [[31]](#_ftn31). CC does not provide predictable and dependable computational performance11, [[32]](#_ftn32). Our research has shown how partitions and schedules can be configured to guarantee timing for hard RT applications [[33]](#_ftn33), [[34]](#_ftn34) on distributed MCPs. However, the configuration of a Fog infrastructure to guarantee Quality-of-Control (QoC) and to allow dynamic reconfiguration has not been investigated. In addition, highly critical controllers may also require redundant architectures [[35]](#_ftn35). There are several application classes that share a converged platform, ranging from highly critical control, that must meet deadlines, QoC, where redundancy is needed, to less critical applications where best-effort approaches are sufficient for their operation, as long as they are properly designed and coordinated [[36]](#_ftn36).

In highly distributed large Fog environments there is no single entity that has perfect knowledge about the complete environment, and can perform resource *provisioning*. Instead, middleware is needed, which is software that runs on top of an OS that enables communication and management of data in distributed applications. This makes it necessary to establish lightweight, scalable *middleware*, which can be deployed on FNs, and which is able to interact with other middleware in a distributed way. Hence, approaches from the field of peer-to-peer (P2P) [[37]](#_ftn37) may provide important insights for the field of Fog Computing. Today, there is a lack of resource provisioning approaches taking into account the inherent volatility of FC environments.

***We need research*** to develop resource management and provisioning mechanisms for deploying scalable Fog Computing applications, while guaranteeing the non-functional properties of the virtualized industrial control applications. To support these solutions, we need to develop novel distributed Fog middleware, which is able to manage and provision a group of FNs.

**Dependability services and application modeling****.** With FC, control functions are virtualized and hence can be easily updated and novel functions can evolve over time. For example, data analytic techniques can be used on the data sets produced by the sensors and the control algorithms can be adjusted to optimize production efficiency. However, the new platform has to be dependable in order to be used for safety-critical OT applications. Dependability is the ability to deliver service that can justifiably be trusted, and its attributes are safety, resilience, reliability, security and privacy. For OT applications, the highest priority is *safety* (no risk of harm to human life or the environment) followed by production quality [[38]](#_ftn38). Security and privacy in OT lags behind IT, as the current state of practice is to use “air gaps”, physically isolating sensitive equipment (locked doors and guards) from unsecured networks, which, with the introduction of standard IT systems no longer works [[39]](#_ftn39). For IT, *security* and *privacy* are important, together with reliability, but safety is not considered. The convergence of IT and OT brings new security challenges, exposing previously isolated OT to new types of attacks38, [[40]](#_ftn40). FC introduces new security and privacy challenges that need to be addressed in order to promote such a new computing paradigm [[41]](#_ftn41). FC inherits the CC security issues [[42]](#_ftn42), but these are more critical due to the safety issues of industrial systems. With the exception of very few preliminary papers41, [[43]](#_ftn43), research is still immature.

Industrial systems require *safety assurance*, i.e., the collection and analysis of evidence that hazards and risks have been identified and that they are reduced to an acceptable level. The certification standards used are derivatives of the functional safety standard IEC 61508, such as IEC 61511 for industrial process control. Certification is a highly elaborate and costly [[44]](#_ftn44) process and usually done for monolithic systems [[45]](#_ftn45). Also, the certification standards and processes are rigid and evolve at a much slower pace as compared to the development paradigm shifts.

*Big Data* and *data analytics* drive novel applications in Industry 4.06. Sensors and machines generate huge amounts of data: industrial data is growing faster than any other sector and ‘‘*manufacturing stores more data than any other sector*” [[46]](#_ftn46). Access to industrial data is difficult because of the different data representations used by sensors and machines, data *variety*, and data *velocity*, e.g., the speed at which data is generated. Many applications enable data analytics by storing historical data in the Cloud, and running Machine Learning (ML) algorithms to gain insights that lead to value creation. Existing ML solutions from, e.g., IBM, Google, Microsoft, do not address industrial automation [[47]](#_ftn47) because large amounts of data cannot be moved to the Cloud due to bandwidth constraints, and with OT there are severe computation and storage limitations as we get closer to the machines. There is limited work in applying ML in RT and on distributed data streams, e.g., *distributed learning* [[48]](#_ftn48).

Regarding application development, the CC programming model typically follows a SOA model. CC applications are written using interacting (*micro*)*services*, developed as *containers* which rely on scalable Platform-as-a-Service (PaaS) [[49]](#_ftn49). Although there are many PaaS solutions for the Cloud, no such solutions exist for the Fog, where applications may reside in a continuum involving the machines, in the Fog Nodes, and the Cloud. To unlock the potential of the FC platform, it is necessary to demonstrate how real-life applications can be developed together with key industrial stakeholders. Fog applications have the potential to deliver innovative Industry 4.0 solutions but so far no Fog applications have been successfully developed and demonstrated.

***We need research*** on new approaches for assuring the dependability of the FC platform. The Fog Platform has to provide standardized access to data, and bring computation and storage closer to the machines to enable operational data analytics. Also, novel programming models for Fog applications are needed to develop applications that provide innovative solutions.

[[1]](#_ftnref1) European Parliament, *Industry 4.0 – Digitalisation for productivity and growth*, 2015, <http://goo.gl/MIqAKK>

[[2]](#_ftnref2) European Commission, *A Stronger European Industry for Growth and Economic Recovery*, <https://goo.gl/gGzQwl>

[[3]](#_ftnref3) *DIN/DKE German Standardization Roadmap: Industry 4.0*, Version 2, <http://www.din.de/blob/65354/f5252239daa596d8c4d1f24b40e4486d/roadmap-i4-0-e-data.pdf>

[[4]](#_ftnref4) European Parliament, *General Principles of EU Industrial Policy*, <http://www.europarl.europa.eu/ftu/pdf/en/FTU_5.9.1.pdf>

[[5]](#_ftnref5) European Roadmap for Industrial Process Automation, [http://processit.eu](http://processit.eu/)

[[6]](#_ftnref6) McKinsey&Company, *Industry 4.0 How to navigate digitization of the manufacturing sector*, <https://www.mckinsey.de/files/mck_industry_40_report.pdf>

[[7]](#_ftnref7) *Defining and Sizing the Industrial Internet*, <http://wikibon.org/wiki/v/Defining_and_Sizing_the_Industrial_Internet>

[[8]](#_ftnref8) *Digital Transformation of Industries Demystifying Digital and Securing $100 Trillion for Society and Industry by 2025*, World Economic Forum, Industry Agenda.

[[9]](#_ftnref9) NexDefense Whitepaper, “IT/OT Convergence, Bridging the Divide,” <http://ics.sans.org/media/IT-OT-Convergence-NexDefense-Whitepaper.pdf>

[[10]](#_ftnref10) T. J.  Williams, “The Purdue enterprise reference architecture,” in *Computers in industry*, vol. 24, no. 2, pp.141–158, 1994.

[[11]](#_ftnref11) M. García-Valls, T. Cucinotta, and C. Lu, “Challenges in real-time virtualization and predictable cloud computing,” in *J. of Sys. Architecture*, vol. 60, no. 9, pp. 726–740, 2014.

[[12]](#_ftnref12) IEEE 802.1 Time-Sensitive Networking (TSN) Task Group, <http://www.ieee802.org/1/pages/tsn.html>.

[[13]](#_ftnref13) 5GPPP, 5G and the Factories of the Future, 2015, <https://5g-ppp.eu/wp-content/uploads/2014/02/5G-PPP-White-Paper-on-Factories-of-the-Future-Vertical-Sector.pdf>

[[14]](#_ftnref14) OPC Unified Architecture, [https://opcfoundation.org](https://opcfoundation.org/)

[[15]](#_ftnref15) **F.** **Bonomi** et al. “Fog computing: A platform for internet of things and analytics,” in *Big Data and Internet of Things: A Roadmap for Smart Environments*, pp. 169–186. Springer, 2014.

[[16]](#_ftnref16) European Parliament, Directorate General for Internal Policies, *Industry 4.0—Study for ITRE Committee,* 2016, <http://goo.gl/NBO2Ge>

[[17]](#_ftnref17) **W. Steiner**, **S. Poledna**, “Fog computing as enabler for the Industrial Internet of Things,” in *Elektrotechnik Und Informationstechnik*, vol. 133, no. 7, pp. 1–5, 2016.

[[18]](#_ftnref18) **F. Bonomi** et al. “Fog computing and its role in the internet of things,” in *Proceedings of the 1st ACM Mobile Cloud Computing Workshop*, pp. 13–15, 2012.

[[19]](#_ftnref19) **W. Steiner**, **F. Bonomi**, and H. Kopetz, “Towards Synchronous Deterministic Channels for the Internet of Things,” in *World Forum on IoT,* pp. 433­­–436, 2014.

[[20]](#_ftnref20) OpenFog Consortium, openfogconsortium.org

[[21]](#_ftnref21) <https://www.ge.com/digital/predix>

[[22]](#_ftnref22) <http://www.cisco.com/c/en/us/solutions/internet-of-things/iot-fog-applications.html>

[[23]](#_ftnref23) <https://www.tttech.com/products/industrial/edge-computing-and-control/edge-computing-nerve/>

[[24]](#_ftnref24) **F. Bonomi** et al. “Fog computing: A platform for internet of things and analytics,” in *Studies in Computational Intelligence*, vol. 546, pp. 169–186, 2014.

[[25]](#_ftnref25) I. Stojmenovic, “Fog computing: A cloud to the ground support for smart things and machine-to-machine networks,” in *Telecom. Networks and Appl. Conf.*, pp. 117–122, 2014.

[[26]](#_ftnref26) R. Wilhelm and J. Reineke, “Embedded Systems: Many Cores—Many Problems,” in *Symposium on Industrial Embedded Systems*, 2012.

[[27]](#_ftnref27) Certification Authorities Software Team (CAST), Position Paper CAST-32A—Multi-core Processors, <https://goo.gl/LjrY17>

[[28]](#_ftnref28) **T. Nolte** et al., “Virtualization technologies in embedded real-time systems,” in *IEEE Conference on Emerging Technologies & Factory Automation*, pp.1–8, 2013.

[[29]](#_ftnref29) M. Luvisotto, et al., “Ultra High Performance Wireless Control for Critical Applications: Challenges and Directions,” in *IEEE Trans. on Industrial Informatics*, 2016.

[[30]](#_ftnref30) B. Wittenmark, J. Nilsson, M. Törngren, “Timing Problems in Real-time Control Systems”, in *American Control Conference*,1995.

[[31]](#_ftnref31) **A.V. Papadopoulos**, et al., “Hard Real-Time Guarantees in Feedback-based Resource Reservations,” in *Real-Time Systems*, vol. 51, no. 3, pp. 221–246, 2015.

[[32]](#_ftnref32) **A.V. Papadopoulos**, “Design and Performance Guarantees in Cloud Computing: Challenges and Opportunities,” in *International Workshop on Feedback Computing*, 2015.

[[33]](#_ftnref33) D.Tămaş-Selicean, and **P**. **Pop**, “Design optimization of mixed-criticality real-time embedded systems,” in *ACM Trans. on Embedded Computing Sys.*, 14(3), 2015.

[[34]](#_ftnref34) **S. S. Craciunas** and **R.** **Serna Oliver**, “Combined task-and network-level scheduling for distributed time-triggered systems,” in *Real-Time Systems*, vol. 52, no. 2, 161–200, 2016.

[[35]](#_ftnref35) P. D. Christofides et al., “Distributed model predictive control: A tutorial review and future research directions,” in *Computers and Chemical Eng.*, vol. 51, pp. 21– 41, 2013.

[[36]](#_ftnref36) R. Scattolini, “Architectures for distributed and hierarchical Model Predictive Control – A review,” in *Journal of Process Control*, vol.19, no. 5, pp. 723–731, 2009.

[[37]](#_ftnref37) R. Steinmetz and K. Wehrle, *Peer-to-Peer Systems and Applications*, Springer, 2005.

[[38]](#_ftnref38) Industrial Internet of Things–Volume G4: Security Framework, <http://www.iiconsortium.org/IISF.htm>

[[39]](#_ftnref39) M. Cheminod et al., “Review of Security Issues in Industrial Networks,” in *IEEE Transactions on Industrial Informatics*, vol. 9, no. 1, pp. 277–293, 2013.

[[40]](#_ftnref40) D. Page and J. Hancock. “How secure is your business? Managing the risks that flow from IT/OT convergence”, 2015

[[41]](#_ftnref41) Y. Shanhe et al., “Security and privacy issues of fog computing: A survey,” in *International Conference on Wireless Algorithms, Systems, and Applications*, 2015.

[[42]](#_ftnref42) D. Zissis and D. Lekkas, “Addressing cloud computing security issues,” in *International Journal of Grid Computing and EScience,* vol. 28, 2012.

[[43]](#_ftnref43) I. Stojmenovic et al. “The Fog Computing Paradigm: Scenarios and Security Issues,” in *Federated Conference on Computer Science and Information Systems,* 2014*.*

[[44]](#_ftnref44) R. Cleaveland, “Formal certification of aerospace embedded software,” in *Wksp. on Aviation Software Systems: Design for Certifiably Dependable System*, 2006.

[[45]](#_ftnref45) Adelard. Adelard safety case development manual. Adelard, London, UK, 1998.

[[46]](#_ftnref46) M. Bailly and J. Manyika, ‘‘Is manufacturing ‘cool’ again?’’ in *McKinsey Global Inst.,* Jan. 21, 2013.

[[47]](#_ftnref47) Yin Shen, and Okyay Kaynak. “Big Data for Modern Industry: Challenges and Trends [Point of View],” in *Proceedings of the IEEE,* vol. 103, no. 2, pp. 143–146, 2015.

[[48]](#_ftnref48) T. Adali, D. J. Miller, K. Diamantaras, and **J. Larsen**, “Trends in Machine Learning for Signal Processing,” in *IEEE Signal Processing Mag.*, vol. 28, no. 11, pp. 193–196, 2011.

[[49]](#_ftnref49) C.Pahl, “Containerization and the PaaS Cloud,” in *IEEE Cloud Computing*, vol.3, pp. 24–31, 2015.
