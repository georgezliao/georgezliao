<div align="center">

[![GSoC write-up](https://img.shields.io/badge/GSoC_2026-Write--up-1f6feb?style=for-the-badge&logo=google&logoColor=white)](https://github.com/ML4SCI/SPINN) [![SkyPrint](https://img.shields.io/badge/SkyPrint-Live_site-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.skyprint.photo/)

</div>

---

# George Liao

Hello!
Last summer I contributed to Google Summer of Code for ML4Science and interned at Brown's Dark Matter Lab. Below are my projects: 

---

### [Fused CUDA kernels for higher-order autodiff](https://github.com/georgezliao/Expanded-GPU-Optimization)
One fused kernel replaces the 94-launch autograd path for a PINN residual:
0.131 ms vs 2.109 ms at 16K points on an A5000, 15.3 MiB vs 977.7 MiB peak at
64K. README has the kernel variants that didn't work and the Nsight counters.

### [Java limit order book and tail-latency harness](https://github.com/georgezliao/Java-Trading-Engine)
p99 10.0 µs → 0.5 µs at 1M msg/s, every variant required to match the baseline's
output hash. The ~500 µs tail turned out to be a HashMap resize; the step near
p99.8 is the 1 kHz timer interrupt.

### [TraceLens — per-process syscall and CPU-wait latency with eBPF](https://github.com/georgezliao/eBPF-Agent)
Per-process histograms stay in the kernel. Always-on aggregation costs ~105 ns
per read at ~0% agent CPU; shipping every event costs ~9× more at 500k reads/s,
almost all of it the wakeup.

### [SPINN — PINN ion-trap electrode optimization](https://github.com/ML4SCI/SPINN)
GSoC 2026. PINNs for Paul-trap electrode geometry, and the checks that separate a
real shape improvement from one the optimizer found by fitting the solution.

---

Other repos: [SkyPrint](https://www.skyprint.photo/) (live, flight climate
impact incl. contrails) · [gravitational lensing PINNs](https://github.com/georgezliao/Gravitational-Lensing-PINNs)
(physics losses didn't beat a data-only baseline) · [HerdLab](https://github.com/georgezliao/llm-trading-crowding)
(multi-agent market sim, public-data observer) · [RL Tetris](https://github.com/georgezliao/rl-robot-tetris)
(no learned policy has beaten the baselines yet)

[resume] · [email]
---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>
