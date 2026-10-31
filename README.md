# Jeongmin Kim 👋

**Computer Engineering undergraduate at Inha University**  
Interested in **GPU & parallel computing, systems software, developer tools, and full-stack engineering**.

I like understanding how software behaves—from concurrency and memory access to operating-system scheduling—and turning that understanding into software that can be tested, measured, and used.

## 🔬 Systems & Parallel Computing

### [Parallel Computing Lab](https://github.com/CSE-Shaco/parallel-computing-lab)
**C++11 · OpenMP · CUDA C++ · CMake**

- Compared thread-local counters and mutex synchronization, and evaluated OpenMP scheduling policies under balanced and imbalanced workloads.
- Implemented four CUDA kernels for the uncentered second-moment matrix `XᵀX/m`: direct, shared-memory tiled, coalesced-load tiled, and register-tiled.
- Validated GPU correctness and memory access with CPU references and Compute Sanitizer on an RTX 4060. Across five same-host sweeps, the register-tiled kernel achieved a **1.406× median paired kernel-time speedup** at 1024×512; results varied by shape and exclude data transfers.

[Code & reproducible measurements](https://github.com/CSE-Shaco/parallel-computing-lab) · [CUDA methodology](https://github.com/CSE-Shaco/parallel-computing-lab/blob/main/cuda-kernel-optimization/docs/methodology.md)

### [CPU Scheduling Simulator](https://github.com/CSE-Shaco/cpu-scheduling-simulator)
**C11 · Event-driven simulation · Automated testing**

- Implemented **FCFS, SJF, SRTF, and Round Robin** with arrivals, preemption, context-switch costs, and Gantt timelines.
- Validated scheduling behavior against independent reference calculations and sanitizers.
- Recorded a **116-case** simulation study exploring waiting time, response time, dispatch overhead, and fairness tradeoffs. These are simulated outcomes, not operating-system benchmarks.

[Code & scheduling analysis](https://github.com/CSE-Shaco/cpu-scheduling-simulator)

### [Java Socket Chat](https://github.com/CSE-Shaco/java-socket-chat)
**Java 21 · TCP · Swing · Maven**

- Client-server chat application featuring multithreaded sessions, chat rooms, file transfer, and separate TCP channels.
- Includes protocol validation, bounded outbound queues, and **38 unit tests + 18 real TCP integration tests**.

[Code & architecture](https://github.com/CSE-Shaco/java-socket-chat) · [CI checks](https://github.com/CSE-Shaco/java-socket-chat/actions/workflows/ci.yml)

## 🚀 Developer Tools & Full-Stack Projects

### [Figma PDF Exporter Font Service](https://github.com/CSE-Shaco/figma-pdf-exporter-helper)
**Objective-C · Go · Native OS APIs**

A local relay that helps a Figma PDF export plugin retrieve fonts exposed by Figma Desktop.

- **macOS:** Objective-C, Foundation, libcurl, and launchd.
- **Windows:** Go, per-user service management, and architecture-specific packaging.
- API validation, local-only access restrictions, install/uninstall scripts, and automated tests.

[Source code](https://github.com/CSE-Shaco/figma-pdf-exporter-helper) · [Releases](https://github.com/CSE-Shaco/figma-pdf-exporter-helper/releases)

### GDGoC INHA Community Platform
**Next.js · Spring Boot · PostgreSQL · AWS**

Contributed to the community website and backend as part of a team, including:

- [Presigned file uploads — backend](https://github.com/GDGoCINHA/24-2_GDGoC_Server/pull/327)
- [Major-code normalization & migration — backend](https://github.com/GDGoCINHA/24-2_GDGoC_Server/pull/325)
- [Attendance dashboard — frontend](https://github.com/GDGoCINHA/24-2_GDGoC_Web/pull/325)
- [Onboarding landing page — frontend](https://github.com/GDGoCINHA/24-2_GDGoC_Web/pull/333)

[Frontend repository](https://github.com/GDGoCINHA/24-2_GDGoC_Web) · [Backend repository](https://github.com/GDGoCINHA/24-2_GDGoC_Server)

## 🧰 Technical Toolkit

| Area | Technologies |
| --- | --- |
| **Systems & parallel** | C, C++, CUDA, OpenMP, Linux |
| **Backend** | Java, Spring Boot, PostgreSQL, Redis, Python |
| **Frontend & mobile** | TypeScript, React, Next.js, React Native, Expo |
| **Infrastructure** | Git, Docker, AWS EC2, Nginx, GitHub Actions |
| **Native tooling** | Objective-C, Go, Foundation, libcurl |

## 🤝 Leadership & Education

- **Technical Lead, GDGoC INHA** — collaborative software development, mentoring, and technical coordination.
- **Computer Engineering, Inha University** — coursework in Parallel Programming, Operating Systems, Computer Architecture, Algorithms, Computer Networks, and Data Structures.

## 🧩 Problem Solving

[![Solved.ac Profile](https://mazassumnida.wtf/api/v2/generate_badge?boj=kingjeongmin)](https://solved.ac/kingjeongmin)
