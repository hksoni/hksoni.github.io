---
layout: page
title: Composition Framework for Packet-processing Programs
description:
area: Programmable Networks, P4, Compilers, Automata Theory, Equivalence checking, Bisimulation, Design By Contract, Hoare Logic.
img:
importance: 1
---

__Description:__

The state-of-the-art packet-processing languages, like [P4](https://p4.org/), and
hardware architectures lack mechanisms that allow them to create and reuse code
libraries. My current focus is on enabling a modular approach for the development
of network programs. The goal is to build a composition framework for network 
programs developed for programmable switches and edge hosts with SmartNICs.


Under this project, we
1. Develop optimized composition mechanisms for data plane of network programs. 
The work advances my prior research, [μP4](https://hksoni.github.io/assets/pdf/microp4.pdf),
and [P4Bricks](https://hal.inria.fr/hal-01632431), on data plane of programmable networks.
2. Design and develop control-plane APIs with well-defined semantics for library
modules of network programs to configure data-plane objects in a coordinated way.
3. Develop composable abstractions for programming packet-processing devices at 
the network edge.

We aim to use the framework for incremental and modular development of new 
services and applications for 5G networks. Also, the framework can integrate 
novel applications (performing in-network computing or caching) with 
packet-processing applications required in the networks.


Interested graduate students and postdocs can send me their resumes at hardik.soni@neclab.eu
