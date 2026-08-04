<!-- ────────────────────────────────────────────── -->
<!--  Sheik Shajeen Ahamed — GitHub Profile README   -->
<!--  Senior / Lead / Staff C++ Systems Engineer      -->
<!-- ────────────────────────────────────────────── -->

## Sheik Shajeen Ahamed

**Senior Software Engineer — C++ Systems, Performance, Numerical Computing**

I design and build high-performance computation systems — C++ engines shipped
as shared libraries, cross-language ABI bridges, and distributed async
pipelines that hold up under production load. My work lives at the boundary
between numerical precision and system performance: converting mathematical
prototypes into deterministic, profiling-driven runtimes, measuring what
compilers actually do at translation-unit boundaries, and benchmarking
kernel I/O paths side by side. Currently focused on compiler-level
performance analysis, low-latency system design, and C++ developer tooling.

---

## About

I build software at the systems/performance boundary — computation engines
that are fast, deterministic, and callable from every language the
enterprise uses. I care about what happens at the boundary: between
translation units, between languages, between user space and the kernel.

My experience ranges from embedded Linux patient monitors to
cross-platform numerical runtimes to distributed async compute pipelines.
I convert research prototypes into production systems that are measured,
profiled, and verified — not just once but continuously.

I publish tools that make other C++ developers faster, benchmark compiler
behavior at the microarchitectural level, and maintain that the best
systems are the ones that stop appearing in the on-call rotation.

---

## Core Expertise

| Domain | Details |
|---|---|
| **Modern C++** | C++20, C ABI design, cross-language interop (C++/Fortran/Python/.NET), Windows & Linux |
| **Linux Systems** | Page cache, O_DIRECT, mmap, eBPF, perf, io_uring, huge pages, CPU affinity |
| **Concurrency** | Multithreaded engines, lock-free structures, NUMA-aware pinning, async pipelines |
| **Performance** | Profiling-driven optimization (perf, gprof, Valgrind), microbenchmarking, LTO analysis |
| **Distributed Systems** | RabbitMQ-based async pipelines, backpressure, retry, ELK observability, Docker/Kubernetes |
| **Numerical Computing** | L-BFGS-B, BFGS, Multivariate Normal CDF, GSL, Armadillo, Fortran integration |
| **Build & CI** | CMake, Conan, cross-platform toolchains, GitHub Actions, reproducible builds |
| **Tooling** | Code generation, project scaffolding, VS Code extensions, PyPI |
| **Databases** | SQLite, MySQL |

---

## Featured Projects

### Open-Source

| Project | Description | Technologies |
|---|---|---|
| [cpp-fortran-bfgs](https://github.com/shajeen/cpp-fortran-bfgs) | C++20 ↔ Fortran BFGS optimizer — zero-copy ABI interop, ISO_C_BINDING, Google Benchmark | C++20, Fortran, CMake |
| [tu-boundary](https://github.com/shajeen/tu-boundary) | Cost of crossing a C++ translation-unit boundary — LTO, assembly verification | C++20, Google Benchmark, objdump |
| [page_cache_bench](https://github.com/shajeen/page_cache_bench) | Linux I/O microbenchmarks — pread, mmap, O_DIRECT | C++17, Linux, Google Benchmark |
| [spreadsheet-to-cpplib](https://github.com/shajeen/spreadsheet-to-cpplib) | Spreadsheet → C++ library code generator — published on PyPI | Python, C++, CMake |
| [template-maker](https://github.com/shajeen/template-maker) | CMake + Conan project scaffolding CLI — published on PyPI | Python, CMake, Conan |
| [xmr-forge](https://github.com/shajeen/xmr-forge) | High-performance Monero CPU miner — RandomX, Stratum, async workers | Rust, Tokio, RandomX |

### Professional Work

| Project | Why It Matters |
|---|---|
| **Mathematical Computation Runtime** | Replaced an ~8 s Python prototype with a ~300 ms C++ engine at 1e-07 precision — shipped as cross-platform .dll/.so consumed by .NET, Python, and FastAPI hosts |
| **Cross-Language Execution Platform** | C++ core with C ABI surface, callable from .NET (P/Invoke), Python (Cython), and FastAPI (HTTP) — single source of truth, three language hosts |
| **Distributed Async Compute Pipeline** | RabbitMQ-based pipeline with backpressure, retry, and ELK observability — reduced end-to-end latency by ~30% |
| **Low-Latency Messaging Engine** | C++20 pub/sub core with io_uring, lock-free ring buffers, NUMA-pinned workers — sub-millisecond fan-out |
| **Linux Performance Profiler** | eBPF + perf-based continuous profiler with <1% CPU overhead, adaptive sampling, per-thread runqueue histograms |

---

## Engineering Interests

Low-level systems behavior. Compiler optimization boundaries. Memory
layout and cache coherence. Lock-free concurrency patterns. Kernel I/O
paths and page-cache dynamics. ABI design across language and
translation-unit boundaries. Developer tooling that reduces friction.
Benchmarking as a regression gate.

---

## Current Focus

- Compiler-level performance analysis — inlining, LTO, IPO boundaries
- Building cross-language ABI bridges for HPC and numerical workloads
- Expanding the developer tooling pipeline — code generation, project scaffolding, CI automation

---

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | C++ (11/14/17/20), Python, Rust, C#, SQL, Bash |
| **Libraries** | Boost, GSL, Armadillo, Qt, POCO |
| **OS & Platforms** | Linux, Embedded Linux, Windows |
| **Build** | CMake, Conan, Docker, Kubernetes |
| **CI / Testing** | GitHub Actions, gtest, pytest, k6, Testcontainers |
| **Profiling** | perf, eBPF, gprof, Valgrind, ELK, Grafana |
| **Databases** | SQLite, MySQL |
| **Messaging** | RabbitMQ |

---

## Contact

- Portfolio & Blog — [shajeen.dev](https://shajeen.dev)
- LinkedIn — [linkedin.com/in/shajeenahamed](https://www.linkedin.com/in/shajeenahamed/)
- Email — shajeenahmed@gmail.com
