![IPDPS 2025 Logo](/assets/2025-logo-300px.jpg)

# 30th International Workshop on High-Level Parallel Programming Models and Supportive Environments

# Overview
The 30th HIPS workshop, to be held as a full-day meeting at the IPDPS 2025 conference in Milan, Lombardy, Italy, focuses on high-level programming of multiprocessors, compute clusters, and massively parallel machines. Like previous workshops in this series - established in 1996 - this event serves as a forum for research in the areas of parallel applications, language design, compilers, runtime systems, and programming tools. It provides a timely forum for scientists and engineers to present the latest ideas and findings in these rapidly changing fields. In our call for papers, we especially invite papers demonstrating innovative approaches in the areas of emerging programming models for large-scale parallel systems and many-core architectures. This year we will add to the list topics programming models and environments for the Edge-Cloud-HPC Continuum as well as the application of recent AI technologies in high-level programming models.

---
---

# News
## Submission due extended to January 27, 2025, AoE
## Camera ready due extended to March 13th, 2025 AoE
## Workshop program is available below.

---
---

# Program
June 3, 2025 \\
09:00 - 17:35 CEST

## Welcome Remarks
09:00 - 09:05 CEST \\
**Michael Gerndt** (Technical University of Munich)

## Celebrating Three Decades of HIPS
09:05 - 09:30 CEST \\
**Michael Gerndt** (Technical University of Munich)

## Keynote
09:30 - 10:30 CEST \\
**Title: Reflections on 30 years of HPC programming: So many hardware advances, so little adoption of new languages**  \\
**Bradford Chamberlain, Hewlett Packard Enterprise**

Abstract: \\
“Programming language design ceased to be relevant in the 1980s.”  So proclaimed a rejection of one of our first HPC language papers roughly 30 years ago.  Yet since then, programmers have experienced the advent, and rise in popularity, of languages such as Java, Javascript, C#, Python, Go, Swift, Julia, and Rust, among others.  These new languages have clearly made strides in areas such as safety, productivity, and parallelism, and in many cases they have become the favorite day-to-day languages of programmers spanning many disciplines.  However, when we reflect on the past 30 years of programming languages for HPC, the situation is not nearly as rosy.  Though many languages have been developed, and a great deal of interesting and compelling work has been achieved and published at venues like HIPS and IPDPS, the programming models used in practice for HPC are much as they were back then:  Fortran, C, C++, MPI, SHMEM, and OpenMP remain the dominant technologies, and SPMD programming and execution are still very much the norm.

Meanwhile, HPC systems have undergone significant transformations over that same period, incorporating multicore processors, multi-socket compute nodes, high-radix/low-diameter network interconnects, NUMA memory architectures, and the rise of GPU computing.  GPUs in particular have arguably resulted in the largest number of new HPC programming models as the community wrestles with how to program GPU-enabled supercomputers effectively.  In the face of these advances, it can often feel as though we have lost ground in terms of programmer productivity during the HIPS era, as systems have become more complex while programming models have remained relatively static.

In this talk, I will give my perspective on the past 30 years of HPC programming languages and models.  In doing so, I will summarize the challenges and barriers to adopting new models, while also arguing for the continuing importance of striving to develop practical, adoptable languages that address the key concerns of HPC programming: specifying parallelism and locality.  Along the way, I will summarize some of the successes of Chapel, a high-level parallel programming language developed by my team at Cray and HPE.  I will also briefly introduce Arkouda—a supportive environment in the form of an extensible Python library that supports driving HPC systems interactively from the comfort of a Jupyter notebook.  Finally, I will describe a vision for changes to the HPC community’s mindset and practices that would help foster the possibility of adopting new, productive languages going forward.

Biography: \\
Brad Chamberlain is a Distinguished Technologist at Hewlett Packard Enterprise (formerly Cray Inc.) who has spent his career focused on productivity for users of high-performance computing (HPC) systems, particularly through the design and development of the Chapel parallel programming language ([https://chapel-lang.org](https://chapel-lang.org)) as well as contributions to the Arkouda library framework for Python ([https://arkouda-www.github.io/](https://arkouda-www.github.io/)).  He received his Ph.D. in Computer Science & Engineering from the University of Washington in 2001, where he focused on the ZPL data-parallel array language; and he remains associated with the department as an affiliate professor of the Paul G. Allen School.  Brad is a staunch advocate for the importance of better parallel programming languages, models, and tools, particularly for HPC programmers.  He is honored to have the opportunity to speak at HIPS this year, as it’s been an important workshop during his career, serving as the venue for the original Chapel paper and a foundational ZPL paper, among others.

<img src="./assets/Brad-LinuxCon.jpg" style="display: block; margin: 0 auto" width="50%"/>

## Coffee Break
10:30 - 11:00 CEST

## Paper Session One
10:30 - 12:30 CEST

**Serverless IoT Framework**\\
**Isaac Nunez**

**Advances in Semantic Patching for HPC-oriented Refactorings with Coccinelle**\\
**Michele Martone**, Julia Lawall

**SpMM-Bench: Performance Characterization of Sparse Formats for Sparse-Dense Matrix Multiplication**\\
Patrick Flynn, **Xinyao Yi**, Erik Saule, Gokcen Kestor, Yonghong Yan

## Lunch Break
12:30 - 14:00 CEST

## Paper Session Two
14:00 - 16:00 CEST

**The Case for ABI Interoperability in a Fault Tolerant MPI**\\
Yao Xu, Grace Nansamba, **Anthony Skjellum**, Gene Cooperman

**Exploring Communication Anomalies in Chapel**\\
Raneem Abu-Yosef, **Bokyeong Yoon**, Martin Kong

**Implementing Directive-Based Deferred Execution for Effective Network Aggregation**\\
**Aaron Welch**, Oscar Hernandez, Stephen Poole, Wendy Poole

**Data Transfer Schemes in the High-Level Communication Library LAIK**\\
Josef Weidendorfer, Lukas Neef, Robert Hubinger, **Amir Raoofy**

## Coffee Break
16:00 - 16:30 CEST

## Paper Session Three
16:30 - 17:30 CEST

**SYCL for HPC: Adapting to Diverse CPU Architecture**\\
**Ashish Bisht**, Aniket Garade, Deepika H. V., Haribabu P., S. A. Kumar, S. D. Sudarsan

**LibraryX-ASIC: A First Look**\\
Sanil Rao, **Larry Tang**, Franz Franchetti

## Closing Remarks
17:30 - 17:35 PDT \\
**Michel Gerndt** (Technical University of Munich)

---
---

# Registration
Attendance at this workshop is part of the registration for IPDPS 2025. See [here](http://www.ipdps.org/ipdps2025/2025-registration.html) to register.

Note: at least one author of each paper must be registered for the symposium by March 31st in order for the paper to be published in the proceedings. It must be a full registration unless the sole author of the paper is a student.

# Topics of Interest
Topics of interest to the HIPS workshop include but are not limited to:
-  High-level and domain-specific programming systems
-  Language/compiler support for AI/ML and Cybersecurity/Privacy (e.g., ML-based auto-tuning)
-  Application of Large Language Models in high-level programming environments
-  Higher-level programming support for quantum computing/quantum simulation
-  Programming Models and Tools for the	Edge-Cloud-HPC Continuum
-  Task-based programming systems
-  (Scalable) programming tools and tools for power & performance analysis, modeling, monitoring and debugging, and core correctness
-  Compiler analysis and optimization techniques
-  OS and architectural support for parallel programming and debugging
-  Software and system support for extreme scalability including fault tolerance and power-aware HPC
-  Programming environments for	heterogeneous multicore systems and	accelerators such as GPUs and FPGAs
-  Solutions for programming paradigms for GPUs from different hardware vendors
-  Dynamism in applications and system resources
-  Performance portability
- Efforts for improving the sustainability of scientific software
-  Languages and runtime support for multi-science/coupled codes, including but	not limited to ensemble computing and uncertainty quantification
-  New programming languages and constructs	for exploiting parallelism and locality

---
---

# Important Deadlines


Submission due date: <strike>January 17 2025</strike> January 27 2025 (extended), Anywhere on Earth (AoE)

Author notification: February 21st, 2025 AoE

Camera-ready papers: <strike>March 6th, 2025 AoE</strike> March 13th, 2025 AoE

---
---

# Submission
Authors are invited to submit original papers in two separate tracks:

**Full papers** may not exceed 10 single-spaced double-column pages using
10-point size font on 8.5x11 inch pages (IEEE conference style), including
figures, tables, and references. The authors, if accepted, will have the
opportunity to present their work during the workshop.

**Short papers** may not exceed 4 single-spaced double-column pages using
10-point size font on 8.5x11 inch pages (IEEE conference style), including
figures, tables, and references. The authors, if accepted, will have the
opportunity to give a short presentation during the workshop.

All submissions should be formatted according to the IPDPS paper style (IEEE conference style, single-blind).

Please submit papers through [the IPDPS-HIPS Linklings site](https://ssl.linklings.net/conferences/ipdps/?page=Submit&id=HIPSWorkshopFullSubmission&site=ipdps2025)

[HIPS 2025 Call for Papers](./HIPS25_CFP.txt)

[IPDPS 2025 Call for Papers](http://www.ipdps.org/ipdps2025/2025-call-for-papers.html)

---
---

# Proceedings

The accepted full papers will be published in the IPDPS 2025 Workshops proceedings by the IEEE Xplore Digital Library.
(Short papers will not appear in the proceedings.)
Presentation of an accepted paper at the conference is a requirement of publication.
Any paper that is not presented at the conference will not be included in IEEE Xplore.

---
---

# Committees

## Workshop Co-chairs
- Michael Gerndt, Technical University of Munich, Munich, Germany (gerndt.in.tum.de)
- Amir Raoofy, Leibniz Supercomputing Centre, Munich, Germany (amir.raoofy@tum.de)


## Steering Committee
- Rudolf Eigenmann, University of Delaware, USA
- Michael Gerndt, Technische Universität München, Germany
- Frank Mueller, North Carolina State University, USA
- Martin Schulz, Technische Universität München, Germany

## Program Committee
- Ahmad Taraf, TU Darmstadt, Germany
- Andreas Wilhelm, CQSE GmbH, Germany
- Balazs Gerofi, Intel, USA
- Barton Miller, University of Wisconsin, USA
- Bernd Mohr, FZ Jülich, Germany
- Christian Terboven, RWTH Aachen University, Germany
- Giorgis Georgakoudis, Lawrence Livermore National Laboratory, USA
- James Lin, Shanghai Jiao Tong University, China
- Josef Weidendorfer, Leibniz Supercomputing Centre, Munich, Germany
- Michael Philippsen, Friedrich-Alexander University Erlangen-Nürnberg , Germany
- Miwako Tsuji, RIKEN Center for Computational Science, Japan
- Mohak Chadha, Nvidia, Germany
- Mohammad Alaul Haque Monil, Oak Ridge National Laboratory, USA
- Nikela Papadopoulou, University of Glasgow, UK
- Onkar Patil, IBM, USA
- Shajulin Benedict, IIIT Kottayam, India
- Siegfried Benkner, Universität Wien, Austria
- Thomas Fahringer, University of Innsbruck, Austria
- Tomohiro Ueno, RIKEN Center for Computational Science, Japan

[//]: # (William Moses, Massachusetts Institute of Technology, USA)
[//]: # (Jeffrey Young, Georgia Institute of Technology, USA)
[//]: # (Qijing Jenny Huang, NVIDIA, USA)
[//]: # (Oliver Fuhrer, ETH Zurich/MeteoSwiss, Switzerland)
[//]: # "Alexander Pletzer, National Institute of Water and Atmospheric Research (NIWA), New Zealand"

---
---

# History

| Workshop                                                                       | Date            | Location                            |
|--------------------------------------------------------------------------------|-----------------|-------------------------------------|
| [29th HIPS 2024](https://hips2024.github.io/)                                  | May 31st 2023   | San Francisco, California USA       |
| [28th HIPS 2023](https://hips2023.github.io/)                                  | May 15th 2023   | St. Petersburg, Florida, USA        |
| [27th HIPS 2022](https://hips2022.github.io/)                                  | May 30th 2022   | Virtual                             |
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

