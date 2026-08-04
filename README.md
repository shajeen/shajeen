## Sheik Shajeen Ahamed

**Senior Software Engineer**

13+ years building high-performance systems in Modern C++ on Linux.

Modern C++  ·
Linux Systems  ·
Performance Engineering  ·
Distributed Systems  ·
Numerical Computing  ·
Developer Tooling

Chennai, India

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

**Modern C++**
C++20/23 · ABI design · Cross-language interoperability · Windows & Linux

**Linux Systems**
Page cache · O_DIRECT · mmap · eBPF · perf · io_uring · Huge pages · CPU affinity

**Concurrency**
Multithreaded engines · Lock-free structures · NUMA-aware pinning · Async pipelines

**Performance**
Profiling-driven optimization · Microbenchmarking · LTO analysis · Assembly verification

**Distributed Systems**
RabbitMQ pipelines · Backpressure · ELK observability · Docker · Kubernetes

**Numerical Computing**
L-BFGS-B · BFGS · Multivariate Normal CDF · GSL · Armadillo · Fortran integration

**Build & Tooling**
CMake · Conan · Cross-platform toolchains · GitHub Actions · Code generation · PyPI

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

**8 s → 300 ms** &nbsp; Reduced mathematical computation runtime from a Python
prototype to a cross-platform C++ engine at 1e-07 precision, consumed by
.NET, Python, and FastAPI hosts.

**~30% latency reduction** &nbsp; Designed an async RabbitMQ pipeline with
backpressure and ELK observability across horizontally scaled workers.

**Sub-millisecond fan-out** &nbsp; Built a C++20 pub/sub engine on io_uring
with lock-free ring buffers and NUMA-pinned workers.

**&lt;1% CPU overhead** &nbsp; Continuous eBPF + perf-based profiling with
adaptive sampling and per-thread runqueue histograms.

---

## Engineering Interests

- Compiler optimization
- Cache hierarchy
- Memory layout
- ABI interoperability
- Linux kernel I/O
- Performance measurement
- Developer tooling

---

## Current Focus

- Measuring compiler optimization boundaries (LTO, IPO, cross-TU inlining)
- Benchmarking Linux page-cache and I/O paths
- Building cross-language ABI bridges for HPC
- Developing developer tooling for Modern C++ build workflows

---

## Selected Technologies

Modern C++20/23 &nbsp;·&nbsp; Linux &nbsp;·&nbsp; CMake &nbsp;·&nbsp; Conan &nbsp;·&nbsp; Boost &nbsp;·&nbsp; RabbitMQ &nbsp;·&nbsp; Google Benchmark &nbsp;·&nbsp; perf &nbsp;·&nbsp; Valgrind

---

## Contact

- Portfolio & Blog — [shajeen.dev](https://shajeen.dev)
- LinkedIn — [linkedin.com/in/shajeenahamed](https://www.linkedin.com/in/shajeenahamed/)
- Email — shajeenahmed@gmail.com
- Location — Chennai, India
