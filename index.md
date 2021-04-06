---
title: PaPoC Workshop 2021
---

The 8th Workshop on Principles and Practice of Consistency for Distributed Data (PaPoC) will take place virtually on April 26th, 2021, in conjunction with the [EuroSys 2021](https://2021.eurosys.org) conference.
PaPoC 2021 is a successor to previous workshops in this series ([PaPoC 2014](http://eventos.fct.unl.pt/papec/), [PaPoC 2015](http://papoc.di.uminho.pt/), [PaPoC 2016](http://www2.ucsc.edu/papoc-2016/), [PaPoC 2017](http://software.imdea.org/Conferences/PAPOC17/program.shtml), [PaPoC 2018](https://papoc-workshop.github.io/2018/), [PaPoC 2019](https://novasys.di.fct.unl.pt/conferences/papoc19/) and [PaPoC 2020](https://papoc-workshop.github.io/2020/)) which brought together researchers and practitioners in the areas of distributed systems, programming languages, databases, and concurrent programming.

The PaPoC workshop investigates the trade-offs among different consistency models for distributed systems, and their operational characteristics.
While stronger consistency models can be easier for programmers to reason about, weaker consistency models can often provide better availability and performance.
Beyond the well-known tension between Consistency, Availability, and Partition-tolerance, as captured by the CAP theorem, many nuanced consistency models and algorithms have been developed for different purposes.
Distributed consistency models are needed in large-scale datacenter-based systems, but also in edge networks with wide geographic distribution, and even in end-user applications running on mobile devices with intermittent network connectivity.
It is clear that there is no universally best solution for sharing data in these different settings.

In order to address these challenges, the PaPoC workshop brings together theoreticians and practitioners from different horizons: system development, distributed algorithms, concurrency, fault tolerance, databases, programming languages and verification, including both academia and industry.
Topics of interest include (but are not limited to) models and mechanisms for consistency in distributed systems, including replicated data types/CRDTs, causal consistency, transaction isolation levels, hybrid consistency models such as RedBlue consistency, analysis of program correctness with regard to different consistency models, formal verification of consistency properties, and studies of performance, scalability, and programmability.

### Program

The keynote at PaPoC this year will be given by [**Peter Alvaro**](https://people.ucsc.edu/~palvaro/).

**Title: What not where: Sharing in a world of distributed, persistent memory**

**Abstract:**

A world of distributed, persistent memory is on its way. Our programming models traditionally operate on short-lived data representations tied to ephemeral contexts such as processes or computers. In the limit, however, data lifetime is infinite compared to these transient actors. We discuss the implications for programming models raised by a world of large and potentially persistent distributed memories, including the need for explicit, context-free, invariant data references. We present a novel operating system that uses wisdom from both storage and distributed systems to center the programming model around data as the primary citizen, and reflect on the transformative potential of this change for infrastructure and applications of the future.  We focus in particular on the landscape of data sharing and the consequences of globally-addressable persistent memory on existing consistency models and mechanisms.

**Bio:**

Peter Alvaro is an Assistant Professor of Computer Science at the University of California Santa Cruz, where he leads the Disorderly Labs research group ([disorderlylabs.github.io](https://disorderlylabs.github.io)). His research focuses on using data-centric languages and analysis techniques to build and reason about data-intensive distributed systems, in order to make them scalable, predictable and robust to the failures and nondeterminism endemic to large-scale distribution. Peter earned his PhD at UC Berkeley, where he studied with Joseph M. Hellerstein. He is a recipient of the NSF CAREER Award, the Facebook Research Award, the USENIX ATC Best Presentation Award, and the UCSC Excellence in Teaching Award.

### Registration

You can register now for PaPoC 2021 by [registering for Eurosys 2021](https://2021.eurosys.org/registration.html#registration). Registration is FREE. 