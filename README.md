## Sheik Shajeen Ahamed

**Senior Software Engineer**

13+ years building high-performance systems in Modern C++ on Linux.

Performance Engineering &nbsp;·&nbsp; Distributed Systems &nbsp;·&nbsp; Numerical Computing &nbsp;·&nbsp; Cross-language Interoperability &nbsp;·&nbsp; Developer Tooling

Currently building compiler-aware developer tools and performance
benchmarks.

---

## About

I focus on compiler optimization, ABI interoperability, and Linux
performance analysis. My work sits at the intersection of numerical
precision and system performance — converting mathematical prototypes
into deterministic C++ runtimes, measuring what compilers do at
translation-unit boundaries, and benchmarking kernel I/O paths side
by side.

Experience spans embedded Linux (ARM/DSP), cross-platform computation
engines, distributed async pipelines, and developer tooling shipped to
PyPI and the VS Code Marketplace.

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

---

## Featured Projects

### Open-Source

[cpp-fortran-bfgs](https://github.com/shajeen/cpp-fortran-bfgs)
**C++20 ↔ Fortran BFGS optimizer — zero-copy ABI interop, ISO_C_BINDING, Google Benchmark**
Demonstrates production-quality ABI interoperability between Modern C++ and
Fortran for HPC workloads.

[tu-boundary](https://github.com/shajeen/tu-boundary)
**Cost of crossing a C++ translation-unit boundary — LTO, assembly verification**
Quantifies what inlining, IPO, and LTO actually save. Backed by objdump
verification.

[page_cache_bench](https://github.com/shajeen/page_cache_bench)
**Linux I/O microbenchmarks — pread, mmap + MADV_RANDOM, O_DIRECT**
Side-by-side comparison of kernel I/O paths under random 4 KB access.

[spreadsheet-to-cpplib](https://github.com/shajeen/spreadsheet-to-cpplib)
**Spreadsheet → C++ library code generator**
Translates XLSM/CSV into CMake-ready C++ projects. Published on PyPI.

[template-maker](https://github.com/shajeen/template-maker)
**CMake + Conan project scaffolding CLI**
Generates complete C++ application and library project structures. Published
on PyPI.

[xmr-forge](https://github.com/shajeen/xmr-forge)
**High-performance Monero CPU miner — RandomX, Stratum, async workers**
Rust systems programming with Tokio async runtime, FFI to C RandomX, and
Linux performance tuning.

### Professional Work

Passing down a production computation workload through 4 stack layers, from
an 8-second research prototype to a ~300 ms cross-platform C++ engine at
1e-07 precision, consumed by .NET, Python, and FastAPI hosts.

Designing an async RabbitMQ pipeline with backpressure and ELK
observability, cutting end-to-end latency by ~30%.

Building a C++20 pub/sub engine on io_uring with lock-free ring buffers
and NUMA-pinned workers — sub-millisecond fan-out.

Continuous eBPF + perf-based profiling with &lt;1% CPU overhead and
per-thread runqueue histograms.

---

## Engineering Interests

Compiler optimization boundaries. Memory layout and cache coherence.
Lock-free concurrency patterns. Kernel I/O paths and page-cache dynamics.
ABI design. Developer tooling that reduces friction. Benchmarking as a
regression gate.

---

## Current Focus

- Measuring compiler optimization boundaries (LTO, IPO, cross-TU inlining)
- Benchmarking Linux page-cache and I/O paths
- Building cross-language ABI bridges for HPC
- Developing developer tooling for Modern C++ build workflows

---

## Tech Stack

**Modern C++20/23 &nbsp;·&nbsp; Linux &nbsp;·&nbsp; CMake &nbsp;·&nbsp; Conan &nbsp;·&nbsp; Boost &nbsp;·&nbsp; RabbitMQ &nbsp;·&nbsp; Google Benchmark &nbsp;·&nbsp; perf &nbsp;·&nbsp; Valgrind**

Also &nbsp; Python &nbsp;·&nbsp; Rust &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Kubernetes &nbsp;·&nbsp; eBPF &nbsp;·&nbsp; ELK &nbsp;·&nbsp; GitHub Actions

---

## Contact

- Portfolio & Blog — [shajeen.dev](https://shajeen.dev)
- LinkedIn — [linkedin.com/in/shajeenahamed](https://www.linkedin.com/in/shajeenahamed/)
- Email — shajeenahmed@gmail.com
