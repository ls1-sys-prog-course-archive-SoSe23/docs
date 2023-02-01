# Practical course: Advanced Systems Programming in C/Rust -- SoSe 2023

## Chair website

- The practical course is organized by the [Chair of Distributed Systems & Operating Systems](https://dse.in.tum.de/) at TU Munich.

## Course Information
- Language: English
- Type: Practical training
- Module: IN0012, IN2106, IN2128
   - (_*This course is not offered to IN2397*_)
- SWS: 6
- ECTS Credits: 10
- Prereqisites:
    - We don't have any compulsory pre-requisites, but we prefer students to be proficient in the basic concepts of operating systems and systems programming (C/C++/Rust).
    - Preferred knowledge or equivalent to the lectures:
        - Fundamentals of Programming (IN0002)
        - Introduction to Computer Architecture (IN0004)
        - Basic Principles: Operating Systems and System Software (IN0009)
- Course Material:
    - The Linux Programming Interface – Michael Kerrisk
    - Linux System Programming – Robert Love
- TUM Online: You must register for this course in TUM Online before the course starts
- Student note: Compulsory enrollment after two weeks of the matching outcome; students who fail to de-register in this period will be registered for the exam

## Course Details
This course covers some of the most important aspects of systems' programming.
More specifically, we will cover the following topics through a set of programming assignments over the semester:

- Kernel and system calls: How programs interact with the operating system, how to implement some system calls yourself in assembly
- File I/O: Learn about file descriptors, direct i/o, memory mapped i/o, page cache etc.
- Concurrency and synchronization: Learn about different threading primitives, i.e., mutexes, concurrent data structure design and how they are implemented
- Processes: Different system calls related to process handling like fork(), execve(), wait()
- Memory management: How virtual memory, heap, stack and how malloc() works
- Networking: How to handle network protocols, efficient ways to implement servers
- Performance: How to bring out the performance of the hardware
- Virtualization: Hypervisors, containers, cgroups
- Compilers: How to convert high-level languages into binary code and how to manipulate them

This course consists of a set of modules related to different aspects of systems programming.
For each of these modules, there is a dedicated assignment that will help students dig deeper into the concepts and get familiar with them with actual, useful, hands-on tasks.
There is also weekly Q&A meeting where we answer students' questions and discuss the specific goal of each assignment.
The students will be required to perform tasks within a time frame (around 2-3 weeks depending on the task) and submit their work in the online evaluation system.
The submitted workpieces will then be evaluated, and based on that, a grade will be calculated for each assignment.

## Objectives
- Introduction to a variety of operating system concepts
- Techniques for debugging and optimization of low-level code
- Good understanding of memory- and resource management

## Meeting place

- Preliminary meeting: February 6th (Mon), 2023 11:00 AM CET at online (zoom)
    - [Zoom link](https://tum-conf.zoom.us/j/63716968522?pwd=RXBrMTdCRnZGMkI1MDVKVEFWODh0UT09)
    - Meeting ID: 637 1696 8522
    - Passcode: 086604

## Tasks

Please refer to the respective task repositories (that are released on the published date) for detail.
The schedule may change. **All deadlines are at 16:00.**

| Task                                                                     | Organizer                                         | Published on | Deadline | Points | Slide                                       | Video                                                                         |
|--------------------------------------------------------------------------|---------------------------------------------------|--------------|----------|--------|---------------------------------------------|-------------------------------------------------------------------------------|
| [Introduction](https://github.com/ls1-sys-prog-course/task0-sort)        | [Masanori](https://github.com/mmisono)            | 17.04.23     | 01.05.23 | 0      | [link](./slides/00-introduction.pdf)        |                                                                               |
| [System Calls](https://github.com/ls1-sys-prog-course/task1-syscalls)    | [Sebastian](https://github.com/Sebastian-Reimers) | 24.04.23     | 08.05.23 | 30     | [link](./slides/01-system_calls.pdf)        | [Lecture](https://youtu.be/qO33G1od3Xo)                                       |
| [File I/O](https://github.com/ls1-sys-prog-course/task2-fileio)          | [Babis](https://github.com/cmainas)               | 08.05.23     | 22.05.23 | 30     | [link](./slides/02-files.pdf)               | [Lecture](https://youtu.be/wDPH8DYZwCg)                                       |
| [Processes](https://github.com/ls1-sys-prog-course/task3-processes)      | [Jiyang](https://github.com/jedichen121)          | 15.05.23     | 29.05.23 | 30     | [link](./slides/03-processes.pdf)           | [Lecture](https://youtu.be/qNzgterdPng)                                       |
| [Concurrency](https://github.com/ls1-sys-prog-course/task4-concurrency)  | [Fransisco](https://github.com/FranciscoRomao)    | 22.05.23     | 05.06.23 | 30     | [link](./slides/04-concurrency.pdf)         | [Lecture](https://youtu.be/Bj-1pFh8Bck)                                       |
| [Memory Management](https://github.com/ls1-sys-prog-course/task5-memory) | [Sebastian](https://github.com/Sebastian-Reimers) | 05.06.23     | 19.06.23 | 30     | [link](./slides/05-memory_management.pdf)   | [Lecture](https://youtu.be/1LxVzohqRx0)                                       |
| [Networking](https://github.com/ls1-sys-prog-course/task6-sockets)       | [Jiyang](https://github.com/jedichen121)          | 12.06.23     | 26.06.23 | 30     | [link](./slides/06-network_programming.pdf) | [Lecture](https://youtu.be/fDRaXnhjoDE)                                       |
| [Performance](https://github.com/ls1-sys-prog-course/task7-performance)  | [Tianchi](https://github.com/lialittis)           | 19.06.23     | 03.07.23 | 40     | [link](./slides/07-performance.pdf)         | [Lecture](https://youtu.be/o1SkOoCyHDI)                                       |
| [Virtualization](https://github.com/ls1-sys-prog-course/task8-container) | [Babis](https://github.com/cmainas)               | 26.06.23     | 10.07.23 | 40     | [link](./slides/08-container.pdf)           | [Lecture](https://youtu.be/GMs3kLteZvk), [Task](https://youtu.be/INyb4Rj073U) |
| Compilers                                                                | [Martin](https://github.com/martin-fink)          | 03.07.23     | 17.07.23 | 40     |                                             |                                                                               |

## Grades

Grades are computed as follow:

|From| To|Grade|
|----|---|-----|
|0   |120| 5.0 |
|121 |135| 4.7 |
|136 |150| 4.3 |
|151 |165| 4.0 |
|166 |180| 3.7 |
|181 |195| 3.3 |
|196 |210| 3.0 |
|211 |225| 2.7 |
|226 |240| 2.3 |
|241 |255| 2.0 |
|256 |270| 1.7 |
|271 |285| 1.3 |
|286 |300| 1.0 |

## Slack workspace

We will use Slack for all communication. Please enroll in our Slack workspace using your official TUM email address.

- **Slack workspace:** https://ls1-courses-tum.slack.com
- **Slack channel:** #ss-23-sys-prog

## Other resources

- [Youtube playlist](https://www.youtube.com/playlist?list=PLfKm1-FQibbAdPAHgK5Pv8LNRr0o4vou7)
- [Bugtracker](https://github.com/ls1-sys-prog-course/docs/issues)
- [Docker image](https://github.com/orgs/ls1-courses/packages/container/package/ls1-runner)
- [The previous semister (SoSe22)](https://github.com/ls1-sys-prog-course-archive-SoSe22/docs)
  - NOTE: The course material is being kept updated; therefore, the old version has differences.

## Contact

We *strongly* prefer slack for all communications. For any further questions/comments, please contact the course organizer(s):

- [Dr. Masanori Misono](https://mmisono.github.io/)
- [Prof. Bhatotia](https://dse.in.tum.de/bhatotia/)

