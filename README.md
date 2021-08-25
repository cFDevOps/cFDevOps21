# 2nd Workshop on DevOps support for Cloud FPGA platforms

## Why is cFDevOps important?

With the slowdown of Moore's law as we know it, the Cloud is resorting to heterogeneous, accelerated computing to satisfy the ever-increasing demand for performance and power efficiency. In just a few years, FPGAs have emerged as compute accelerators next to GPUs and are part of the standard offerings from many Cloud vendors. However, the development environment, deployment procedures, security measures, and monitoring tools are different for each platform and the portability of the FPGA kernel designs remains limited.

In this workshop, leading platform providers, designers of development environments, and developers are going to present the state-of-the-art for Cloud FPGA platforms and explore opportunities and directions for future improvements from the developer's point of view. Instead of focusing on the performance and optimization of a specific application, the goal of this workshop is to highlight the challenges, which a Cloud application developer faces when designing, implementing, deploying, scaling and debugging Cloud services on Cloud FPGA platforms. A focus area for this years edition are end-to-end toolchains, compilation and debugging tools for distributed FPGA platforms. 

## Program

The workshop will take place on  **Monday, August 30, 14:30h - 18:30h CEST**. The workshop will be held online (Zoom Webinar/Whova platform).

| **Time (CEST)** | **Title**                                                                                            | **Presenters**                                           |
|:---------------:|:---------------------------------------------------------------------------------------------------- |:-------------------------------------------------------- |
| 14:30           | Opening                                                                                              | *The Organizers*                                         |
|                 | **Session 1**                                                                                        | **Development and Debugging of Cloud FPGA applications** |
| 14:40           | On the development of distributed applications with Intel FPGA SDK for OpenCL                        | Tiziano De Matteis, ETH Zürich                           |
| 15:15           | And, what about debugging for multi-FPGA systems?                                                    | Paul Chow, University of Toronto                         |
| 15:50           | climbing EVEREST: dEsign enVironmEnt foR Extreme-Scale big data analyTics on heterogeneous platforms | Christian Pilato, Politecnico di Milano                  |
| 16:25           | Q & A                                                                                                | *Everyone*                                               |
| 16:40           | **Break**                                                                                            |                                                          |
|                 | **Session 2**                                                                                        | **Operation of large Cloud FPGA deployments**            |
| 17:00           | Single-line deployment of Cloud FPGAs                                                                | Chris Kachris, InAccel                                   |
| 17:35           | AQUA (Advanced Query Accelerator) for Amazon Redshift                                                | Andrew Caldwell, AWS Redshift                            |
| 18:10           | Q & A                                                                                                | *Everyone*                                               |
| 18:30           | Closing                                                                                              | *The Organizers*                                         |

## Registration

Registration is mandatory via the FPL registration [here (Whova)]([FPL 2021 - Registration - cfaed](https://cfaed.tu-dresden.de/fpl2021/registration)). The registration is free of charge.

More details about FPL 2021 can be found [here]([FPL 2021 - Welcome - cfaed](https://cfaed.tu-dresden.de/fpl2021/welcome-to-fpl2021)).

## Talks

### Session 1: Development and Debugging of Cloud FPGA applications

#### On the development of distributed applications with Intel FPGA SDK for OpenCL

by ***Tiziano De Matteis, ETH Zürich, Scalable Parallel Computing Laboratory***

**Abstract:** In this talk, we will share our experiences in developing a distributed communication library for multi-FPGA systems (Streaming Messages Interface -- ) and distributed applications that build on top of it.We will present the main challenges that we had to face in developing and emulating such applications, together with our adopted solutions. Finally, we will briefly discuss what we believe are necessary tools to further enable the development/debugging of distributed FPGA programming.

#### And, what about debugging for multi-FPGA systems?

by ***Paul Chow, Professor Computer Engineering & Electronics, University of Toronto***

**Abstract:** In reality, very few beyond Microsoft have built significant multi-FPGA systems.  This means that very few have even thought about how to debug a single application running on multiple FPGAs because the need has not arisen.  Most FPGA designers are familiar with tools such as Intel's SignalTap and the Xilinx ILAs, but they have been mostly debugging one FPGA at a time.  Would you really want to use these tools on an application running on 16 network-connected FPGAs in the cloud?  Can such tools even work in that environment?  In this talk I will present work done at the University of Toronto where we have considered this problem and developed some early-stage techniques to help find bugs and do performance analysis of a multi-FPGA application.

#### climbing EVEREST: dEsign enVironmEnt foR Extreme-Scale big data analyTics on heterogeneous platforms

by ***Christian Pilato, Assistant Professor, Dipartimento di Elettronica, Politecnico di Milano***

**Abstract:** t.b.a.

### Session 2: Operation of large Cloud FPGA deployments

#### Single-line deployment of Cloud FPGAs

by ***Chris Kachris, CEO of InAccel***

**Abstract:** t.b.a.

#### AQUA (Advanced Query Accelerator) for Amazon Redshift

by ***Andrew Caldwell, AWS Redshift***

**Abstract:** t.b.a.

#### ## Organizers

#### Chris Kachris, inaccel, Greece

Chris Kachris the founder and CEO of InAccel that helps companies speedup their applications using hardware accelerators (FPGAs) in the cloud or on-prem. Inaccel, using a unique FPGA orchestrator, allows scalable deployment of FPGA clusters. Chris holds a Ph.D. from Delft University of Technology. He has published more than 70 papers in international journals and conferences with more than 1800 citations. He has over 15 years of experience on FPGAs and he is the editor of the book Hardware Accelerators in Data Centers.

#### Christoph Hagleitner, IBM Research Europe, Switzerland

Christoph Hagleitner leads the cloudFPGA project at the IBM Research Europe Lab (ZRL) in Ruschlikon, Switzerland. He obtained a Ph.D. degree for a thesis on CMOS-integrated Microsensors from ETH, Zurich, Switzerland in 2002. In 2003 he joined IBM Research to work on the system architecture of a novel probe-storage device (“millipede”-project). In 2008, he started to build up a new research group in the area of accelerator technologies. The team initially focused on integrated accelerator cores and gradually expanded its research to heterogeneous computing systems and their applications.

#### Dionysios Diamantopoulos, IBM Research Europe, Switzerland

Dionysios Diamantopoulos is a Post-Doc Researcher in the  Cloud & AI Systems Research department of IBM Research  Europe. Dionysios holds a PhD  from ECE/Technical University of Athens (2015), and a D.Eng. from CEID/University of Patras (2009). Being affiliated with the ICCS, he was enrolled in several research projects from EU (FP7, H2020) and European Space Agency.  Dionysios joined IBM ZRL (2017) as a researcher in Transprecision Computing. His research is disseminated in one book chapter and more than 30 publications in international conferences and journals. He is the co-inventor of  three filed patents and one pending (USPTO). His research interests lie in the system-level specialization that lay the foundation of heterogeneous-accelerated systems for the hybrid cloud era.  He is a member of HiPEAC, IEEE, IEEE CAS and Technical Chamber of Greece. 

#### Burkhard Ringlein, IBM Research Europe, Switzerland

Burkhard Ringlein is a Predoctoral Researcher in the Cloud & AI Systems Research department of the IBM Research Zurich Laboratory and pursues his PhD in cooperation with the Department of Computer Science, Computer Architecture of the Friedrich-Alexander University Erlangen-Nürnberg, Germany. As part of the cloudFPGA project, he is focusing on Distributed Reconfigurable Architectures in the context of High-Performance-Computing and AI Acceleration. 

#### Christian Plessl, Paderborn Center for Parallel Computing, Germany

Christian Plessl is Professor for Computer Science of Paderborn University and director of the Paderborn Center for Parallel Computing (PC²). His research is focussed on reconfigurable architectures, compilation and runtime systems and applications. Leveraging the longstanding expertise in FPGA acceleration at Paderborn University, PC² has for the first time deployed FPGAs in an HPC production system (Noctua) in 2018. This installation serves as a development platform for porting HPC codes and libraries to FPGAs.

## Contact

[Burkhard Ringlein](https://researcher.watson.ibm.com/researcher/view.php?person=zurich-NGL)