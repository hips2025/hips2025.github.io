![IPDPS 2022 Logo](/assets/ipdpslogo2.jpg)

# Overview
The 27th HIPS workshop, proposed as a full-day meeting at the IEEE IPDPS 2022
conference ~~in Lyon, France and~~ as a virtual workshop, focuses on high-level
programming of multiprocessors, compute clusters, and massively parallel
machines. Like previous workshops in the series, which was established in 1996,
this event will serve as a forum for research in the areas of parallel
applications, language design, compilers, runtime systems, and programming
tools. It provides a timely forum for scientists and engineers to present the
latest ideas and findings in these rapidly changing fields. In our call for
papers, we especially encouraged innovative approaches in the areas of emerging
programming models for large-scale parallel systems and many-core
architectures.

# Important Deadlines
Submission due date: February 11, 2022 (Extended) Anywhere on Earth (AoE)

Author notification: March 7th, 2022 AoE

Camera-ready papers: March 21st, 2022 AoE

# Submission
The HIPS paper style is identical to the IPDPS paper style.

**Full papers** may not exceed 10 single-spaced double-column pages using 10-point size font on 8.5x11 inch pages (IEEE conference style), including figures, tables, and references. 

**Short papers** may not exceed 4 single-spaced double-column pages using 10-point size font on 8.5x11 inch pages (IEEE conference style), including figures, tables, and references. 

[IPDPS 2022 Call for Papers](https://www.ipdps.org/ipdps2022/2022-call-for-papers.html)

[Submission Website](https://easychair.org/conferences/?conf=hips22)

# Topics of Interest
Topics of interest to the HIPS workshop include but are not limited to:
- High-level and domain-specific programming systems
- Languages and compilers for post-Moore's-Law (or Post Von Neumann)
- Language/compiler support for AI/ML and Cybersecurity/Privacy (e.g., ML-based auto-tuning)
- Task-based programming systems
- (Scalable) programming tools and tools for power & performance analysis, modeling, monitoring, and debugging and core correctness
- Compiler analysis and optimization techniques
- OS and architectural support for parallel programming and debugging
- Software and system support for extreme scalability including fault tolerance and power-aware HPC
- Programming environments for heterogeneous multicore systems and accelerators such as GPUs and FPGAs
- Solutions for programming paradigms for GPUs from different hardware vendors
- Dynamism in applications and system resources
- Performance portability
- Efforts for improving the sustainability of scientific software 
- Languages and runtime support for multi-science/coupled codes, including but not limited to ensemble computing and uncertainty quantification
- New programming languages and constructs for exploiting parallelism and locality
- Higher-level programming models or languages for quantum computing/quantum simulation
- Efforts in programming models, environments, and experience on emerging computer architectures, such as Cerebras, SambaNova, ARM, etc.

# Registration
Attendance at this workshop is part of the registration for IPDPS 2022. See [here](http://www.ipdps.org/ipdps2022/2022-registration.html) to register.

---
---

# Program
May 30th, 2022 \\
10:00 - 17:20 EDT \\
16:00 - 23:20 CEST

## Welcome Remarks
10:00 - 10:05 EDT \\
16:00 - 16:05 CEST

## Keynote
Chair: Martin Ruefenacht \\
10:05 - 11:00 EDT \\
16:05 - 17:00 CEST

**Deep Learning Recommendation Systems at Scale: A Peek into the Meta's Supercomputing Needs** \\
**Pavan Balaji**

Abstract: \\
Like many other hyperscalar companies, Meta heavily relies on deep
learning in its internal systems for numerous things including
recommending content to the user; understanding text, speech, and
visual content to recognize things such as hate speech; and
personalizing advertisements based on user preferences.  Training and
serving such deep learning models places tremendous requirements on
how we design and use our supercomputing systems.  In this
presentation, I'll talk about a subset of Meta's internal deep learning
system requirements, primarily those targeting our recommendation
models.  I'll talk about our computational, memory, network, and
storage requirements.  I'll discuss how performance and
performance/watt have become a crucial metric of competitiveness for
Meta, and the kind of optimizations we do to meet these demands.
Finally, I'll discuss how some of the standard programming models,
such as MPI and OpenMP, are falling short in meeting our demands
leading us to develop our own in many cases.

Biography: \\
Dr. Pavan Balaji holds an appointment as an Applied Research
Scientist, Technical Lead, and Manager, at Meta AI where he leads the
HPC Network Communications and Early Industry Partnerships Group.
Before joining Meta, he was a Senior Computer Scientist and Group Lead
at the Argonne National Laboratory, where he lead two groups:
Programming Models and Runtime Systems and Future Architectures for
AI.  His research interests include HPC hardware/software codesign for
AI workloads, communication runtime systems, networks, and scale-out
techniques, parallel programming models and runtime systems for
communication and I/O on extreme-scale supercomputing systems, modern
system architecture, cloud computing systems, and data-intensive
computing.  He has more than 200 publications in these areas and has
delivered more than 200 talks and tutorials at various conferences and
research institutes.  He is a recipient of several awards including
the IEEE TCSC Award for Excellence in Scalable Computing (Middle
Career) in 2015; TEDxMidwest Emerging Leader award in 2013;
U.S. Department of Energy Early Career award in 2012; Crain's Chicago
40 under 40 award in 2012; Los Alamos National Laboratory Director's
Technical Achievement award in 2005; Ohio State University Outstanding
Researcher award in 2005; best paper awards at PACT 2019, ACM HPDC
2018, IEEE ScalCom 2013, Euro PVM/MPI 2009, ISC 2009, IEEE Cluster
2008, Euro PVM/MPI 2008, ISC 2008; best paper finalist at IEEE/ACM SC
2014; best poster award at IEEE ICPADS 2018; best poster finalist at
IEEE/ACM SC 2014; and best student poster award at ICPP 2018.  He has
served as a chair or editor for nearly 100 journals, conferences and
workshops, and as a technical program committee member in numerous
conferences and workshops.  He is a senior member of the IEEE and a
distinguished member of the ACM.  More details about Dr. Balaji are
available at https://pavanbalaji.github.io.

## Break
11:00 - 11:15 EDT \\
17:00 - 17:15 CEST

## Session One: Distributed Memory
Chair: Martin Ruefenacht \\
11:15 - 12:45 EDT \\
17:15 - 18:45 CEST

**Towards Java-based HPC using the MVAPICH2 Library: Early Experiences** \\
Kinan Al-Attar, Aamir Shafi, Hari Subramoni, and Dhabaleswar K. Panda

**mpisee: MPI Profiling for Communication and Communicator Structure** \\
Ioannis Vardas, Sascha Hunold, Jordy I. Ajanohoun, and Jesper Larsson Träff

**An On-the-Fly Method to Exchange Vector Clocks in Distributed-Memory Programs** \\
Simon Schwitanski, Felix Tomski, Joachim Protze, Christian Terboven, and Matthias S. Müller

## Lunch Break
12:45 - 13:15 EDT \\
18:45 - 19:15 CEST

## Invited Talk
Chair: Martin Ruefenacht \\
13:15 - 14:00 EDT \\
19:15 - 20:00 CEST

**Heterogeneous quantum computing - developing the generation of quantum processors** \\
**Bettina Heim**

## Session Two: Shared Memory
Chair: Martin Ruefenacht \\
14:00 - 15:00 EDT \\
20:00 - 21:00 CEST

**Automatic Parallelization of Programs via Software Stream Rewriting** \\
Tao Tao and David Plaisted

**Decentralized in-order execution of a sequential task-based code for shared-memory architectures** \\
Charly Castes, Emmanuel Agullo, Olivier Aumage, and Emmanuelle Saillard

## Break
15:00 - 15:15 EDT \\
21:00 - 21:15 CEST

## Session Three: Heterogenous
Chair: Amir Raoofy \\
15:15 - 17:15 EDT \\
21:15 - 23:15 CEST

**Evaluating Unified Memory Performance in HIP** \\
Zheming Jin and Jeffrey Vetter

**Improving Scalability with GPU-Aware Asynchronous Tasks** \\
Jaemin Choi, David F. Richards, and Laxmikant V. Kale

**A Customizable Lightweight STM for Irregular Algorithms on GPU** \\
Shayan Manoochehri, Patrick Cristofaro and Dhrubajyoti Goswami

**Concurrent CPU-GPU Task Programming using Modern C++** \\
Tsung-Wei Huang

## Closing Remarks
17:15 - 17:20 EDT \\
23:15 - 23:20 CEST

---
---

# Committees

## Workshop Co-chairs
- Jiajia Li, College of William and Mary, jli49 at wm.edu
- Martin Ruefenacht, Leibniz Supercomputing Centre, martin.ruefenacht at lrz.de

## Steering Committee
- Rudolf Eigenmann, University of Delaware, USA
- Michael Gerndt, Technische Universität München, Germany
- Frank Mueller, North Carolina State University, USA
- Craig Rasmussen, University of Oregon, USA
- Martin Schulz, Technische Universität München, Germany

## Program Committee
- Mehmet Esat Belviranli, Colorado School of Mines, USA
- Guoyang Chen, Qualcomm Inc., USA
- Huimin Cui, Institute of Computing Technology, Chinese Academy of Sciences, China
- Anthony Danalis, University of Tennessee, USA
- Bettina Heim, Microsoft, USA
- Jianyu Huang, Facebook, USA
- Pengcheng Li, Google, USA
- Seyong Lee, Oak Ridge National Laboratory, USA
- Ang Li, Pacific Northwest National Lab, USA
- Reed M. Milewicz, Sandia National Laboratories, USA
- Kenneth J. Roche, Pacific Northwest National Lab, USA
- Piyush Sao, ORNL, USA
- Sameer Shende, University of Oregon, USA
- Zheng Wang, University of Leeds, United Kingdom
- Jeffrey Young, Georgia Institute of Technology, USA

# History

| Workshop                                                                       | Date            | Location                            |
|--------------------------------------------------------------------------------|-----------------|-------------------------------------|
| [26th HIPS 2021](https://www.cs.wm.edu/~bren/HIPS_2021.htm)                    | May 17th 2021   | Virtual                             | 
| [25th HIPS 2020](https://faculty.ucmerced.edu/dong-li/HIPS_2020.htm)           | May 18th 2020   | New Orleans, Louisiana, USA         |
| [24th HIPS 2019](https://hosting.cs.vt.edu/hips2019/)                          | May 20th 2019   | Rio de Janeiro, Brazil              |
| [23rd HIPS 2018](http://hips2018.mnm-team.org/)                                | May 21st 2018   | Vancouver, British Columbia, Canada |
| [22nd HIPS 2017](https://inside.mines.edu/~bwu/sites/HIPS2017/)                | May 29th 2017   | Orlando, FL, USA                    |
| 21st HIPS 2016                                                                 | May 23rd 2016   | Chicago, IL, USA                    |
| [20th HIPS 2015](https://hpc.pnl.gov/conf/hips/2015/)                          | May 25th 2015   | Hyderabad, India                    |
| [19th HIPS 2014](https://www.eecis.udel.edu/~cavazos/hips/)                    | May 19th 2014   | Phoenix, AZ, USA                    |
| 18th HIPS 2013                                                                 | May 20th 2013   | Boston, MA, USA                     |
| 17th HIPS 2012                                                                 | May 21st 2012   | Shanghai, China                     |
| [16th HIPS 2011](http://www.unixer.de/hips2011/)                               | May 20th 2011   | Anchorage, Alaska, USA              |
| 15th HIPS 2010                                                                 | April 19th 2010 | Atlanta, GA, USA                    |
| 14th HIPS 2009                                                                 | May 25th 2009   | Rome, Italy                         |
| 13th HIPS 2008                                                                 | April 14th 2008 | Miami, FL, USA                      |
| [12th HIPS 2007](https://www.cs.rochester.edu/~cding/Announcements/HIPS07/)    | March 26th 2007 | Long Beach, California, USA         |
| 11th HIPS 2006                                                                 | April 25th 2006 | Rhodes Island, Greece               |
| 10th HIPS 2005                                                                 | April 4th 2005  | Denver, Colorado, USA               |
| 9th HIPS 2004                                                                  | April 26th 2004 | Santa Fe, New Mexico, USA           |
| 8th HIPS 2003                                                                  | April 22nd 2003 | Nice, France                        |
| 7th HIPS 2002                                                                  | April 15th 2002 | Fort Lauderdale, FL, USA            |
| 6th HIPS 2001                                                                  | April 23rd 2001 | San Francisco, CA, USA              |
| 5th HIPS 2000                                                                  | May 1st 2000    | Cancun, Mexico                      |
| 4th HIPS 1999                                                                  | April 12th 1999 | San Juan, Puerto Rico, USA          |
| 3rd HIPS 1998                                                                  | March 30th 1998 | Orlando, FL, USA                    |
| 2nd HIPS 1997                                                                  | April 1st 1997  | Geneva, Switzerland                 |
| 1st HIPS 1996                                                                  | April 16th 1996 | Honolulu, HI, USA                   |
