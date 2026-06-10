---
title: "Nordic IoT Summer School 2019: Edge and Fog Computing"
permalink: /activities/nordic-iot-summer-school-2019-edge-and-fog-computing/
---

## FORA Training School (TS2)

2019, June 17th-21st, Copenhagen

##### 

##### About

The Nordic IoT Summer School is a week-long intensive introduction to all aspects of IoT systems. Rich sensor systems and distributed computation allow computing systems to measure and interact with the physical world. These emerging IoT systems will necessarily stretch from edge and fog computing devices that connect to cloud servers. Challenges at all levels of abstraction—devices, software, networks, architectures, and applications—must be faced to deliver on the potential of IoT systems technology.

Topics range across the design stack and network: low power VLSI edge devices, signal processing and control, security, algorithms, applications.

This summer school is a successor to two traditions: the DTU summer session on embedded computing and Georgia Tech summer schools on IoT and CPS.

##### Organizers:

- Prof. Jan Madsen, Head of Section for Embedded Systems Engineering, Deputy Director of Department of Applied Mathematics and Computer Science (DTU Compute), **Technical University of Denmark**
- Prof. Marilyn Claire Wolf, Rhesa “Ray” S. Farmer Distinguished Chair of Embedded Computing Systems and Georgia Research Alliance Eminent Scholar, **Georgia Institute of Technology**

##### Program

###### Monday, June 17

- **The new ISO/IEC 30141 – IoT reference architecture,** Anders Mynster

*Anders Mynster is a standardization expert in ISO/IEC SC41, chair of the IEEE European public policy committee on ICT, member of the standardization political forum and the Danish standards institute and member of the EU technical expert group at the Danish industry association. In this presentation Anders will takes us through the new ISO/IEC 30141 – IoT reference architecture. That can serve as a technical overview of the technical building blocks, essential for creating a new architecture. It also introduces characteristics that are essential to an IoT solution and the roles needed for the development, service delivery and users. After the break, Anders will takes us through the essential requirements for the inner market in Europe to get the CE marking, ie. The New legislative framework directives and the associated standards. Lastly he will briefly talk about the political trends in cybersecurity in relation to standardized and harmonized requirements.*

- **Designing Ultra-Low Power Medical Wearables for the Internet of Things Era,** Associate Prof. David Atienza

The Internet of Things (IoT) has been hailed as the next frontier of innovation in which our everyday objects are connected in ways that improve our lives and transform industries. The IoT concept is poised to change the way medical wearables are designed and connecting all of us to advanced healthcare services, but major key challenges remain in achieving this potential due to inherent resource-constrained nature of IoT wearables, coupled with the computing power requirements of Big Data medical applications, which can result in degraded and unreliable behavior of IoT medical devices, or a global energy crisis when IoT is fully deployed in the future. In this keynote David Atienza will first discuss the challenges of ultra-low power design and communication in medical wearables for the IoT era and their potential system misbehavior induced by reliability issues and scaled voltages. Then, he will showcase the opportunities for next-generation smart medical wearables that combine new embedded systems architecture including novel nanotechnologies and a better understanding on how living organisms operate with advanced machine learning techniques, in order to gracefully scale the energy consumption and precision of the medical applications to the requirements of our surrounding IoT world.

###### Tuesday, June 18

- **Efficient IoT Design**, Prof. Jörg Henkel

This lecture focuses on efficient design of IoT from the angles of various application scenarios:

1. 1. As the number of IoT devices increases, we face a hard-to-manage volume of IoT data. Varieties of approaches are needed to address this issue. Edge computing is to move the data processing task closer to its source (embedded device). Meanwhile, the constrained computational resources at the edge (gateways and embedded devices) introduce another challenge: managing limited shared resource between IoT devices. The communication bandwidth as well as storage and computation capabilities of devices are limited and yet are shared among multiple devices. It calls for fast and low-overhead resource allocation.
   2. The massive number of IoT and connected devices constantly collect data using various sensors. The goal of IoT is to provide advanced monitoring and control systems based on this data. Hence, the inference from data is of crucial importance in IoT. Among the means and tools and techniques for data processing and information inference, machine learning has showed a great potential and gained popularity. Various IoT applications involve with either 1) detection problem (e.g. normal/abnormal) which is a classification problem, or 2) prediction problem (e.g. number of users, energy usage, etc.) which is a regression problem, or 3) making decisions and taking actions at runtime which can be modeled as a reinforcement problem. Machine learning provides techniques and models to solve such problems. Analyzing the usage of machine learning in IoT domain showed a recent boost particularly for deep neural network, security, and edge computing. Among the application domains, smart home, image/video classification and especially healthcare have received a great attention in research sector.
   3. In the medical and healthcare domain, the combination of low-power embedded devices and efficient/novel computation techniques has enabled the detection and prediction of diseases or unhealthy behaviors. In one case-study, an accurate and low-overhead algorithm is designed to predict the epileptic seizure on wearable devices. The collected biomedical Electroencephalogram (EEG) signal from the head skin reveals the brain activity and is used to predict seizure attacks by detecting the pre-ictal state. Machine learning classification models are trained using offline data and optimized for low-resource processors. To achieve that, new distinctive features are extruded from the EEG signal at runtime.

The lecture starts with a survey of IoT technologies for embedded computing and provides as well an overview of machine learning for IoT.

- **IoT and edge intelligence,** Prof**.** Marilyn Wolf

*Edge Intelligence is the intersection of Internet-of-Things technology and machine learning. Machine learning has great promise in many applications that are also relevant to IoT. IoT technological capabilities (limited bandwidth, low power) and application constraints (privacy, latency) suggest that not all machine learning can be performed in the cloud. This talk will survey IoT system architecture characteristics, motivate the need for machine learning in IoT applications, discuss relevant challenges and survey recent work in the area.*

###### Wednesday, June 19

- **Turning IoT Devices into Robust and Safe Computers,** Claus Bak Petersen, COO Toitware

Small IoT devices are inherently brittle to program due to lack of memory protection, limited resources, and only a thin layer of operating system support. Developers link all the firmware together and deploy it as a whole, thus making every single change a full, reboot-required system update that potentially wrecks havoc with the overall system integrity. Isn’t it time that we make the platforms more modern and robust – and start deploying and updating software components and apps independently?

**Bio:** COO Claus Bak Petersen, Toitware has more than 30 years of experience in founding, growing, and running companies and taking them from an idea to global commercial success. His background is electronics engineering and his product expertise spans both cloud solutions and embedded hardware. He holds an MSc from DTU.

- **Digital disruption,** Andreas Claudi

Disruption occurs faster and faster and virtually all industries and subjects are affected. The last wave of Disruption is Analytics / Big Data / AI, and it is clear that there are huge gains to be gained, both for cost, service level and earnings.

Digital disruption remains challenging as the strategies are complex and multidimensional, and even when the strategy is clear, digital transformations are still extremely complex to implement as they cross organizational and technical dimensions.

This talk seeks to cover three dimensions of Digital disruption;

1) How to formulate a digital strategy, resulting in a portfolio of strategic projects

2) How to execute the strategy across organizational and technical boundaries

3) How to observe results so that execution can be adjusted

###### Thursday, June 20

- **Applications**, Karl-Erik Arzen
- **Network Security for Low-End IoT Devices,** Assistant Prof. Fontas Fafoutis

At the lower end of the IoT spectrum, we find sensors and other data generating devices that are characterised by severe resource constraints: they are often battery-powered and have low resources in terms of processing power and memory. These devices generate raw data, which are, in turn, transferred over a low-power wireless network to an IoT gateway that lies in the root of the low-power network. Thereafter, the raw data are either processed at the IoT gateway, following the principle of Fog Computing, or transferred and processed at the cloud, following the principle of Cloud Computing. In this lecture, we will focus on the security aspects of the low-power wireless network that provides the necessary infrastructure for raw data acquisition. In the first part of the lecture, we will introduce low-power wireless networking standards, as well as their security features. We will focus, in particular, on the ‘Industrial Internet’ protocol stack proposed by the IETF, which aims to bring the reliability of industrial wireless standards in low-power IPv6 networks. In the second part of the lecture, we will discuss about the challenge of encryption key distribution in low-end IoT devices; we will discuss practical ways to install static encryption keys in large-scale deployments.

###### Friday, June 21

- **The Internet-of-Bio-NanoThings,** Prof. Jan Madsen

The Internet-of-Things is a core technology for realizing the full potential of the Industry 4.0 vision. It has been made possible by the exponential growth in computing power, storage capacity and communication bandwidth fueled by Moore’s Law. Until now, we have largely focused on instrumenting and controlling our macro world – smart manufacturing, smart cities and smart healthcare – to name a few. But what will happen when we are able to monitor and control at the nano-scale? The internet-of-Bio-NanoThings promises to enable applications such as intra-body sensing and actuation networks, and environmental control of toxic agents and pollution. This is a paradigm-shifting concept for computing, communication and network engineering, where novel challenges are faced to develop efficient and safe techniques for computing and for the exchange of information, interaction, and networking within the biochemical domain, while enabling an interface to the electrical domain of the Internet.

- **What have we learned?**
