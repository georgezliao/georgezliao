<div align="center">

[![GSoC write-up](https://img.shields.io/badge/GSoC_2026-Write--up-1f6feb?style=for-the-badge&logo=google&logoColor=white)](https://github.com/ML4SCI/SPINN) [![SkyPrint](https://img.shields.io/badge/SkyPrint-Live_site-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.skyprint.photo/)

</div>

---

## `> Who is George?`

```python
class GeorgeLiao:
    school    = "Brown University"
    interests = ["DL", "GPU performance", "RL", "systems"]
    stack     = ["Python", "PyTorch", "C/C++", "CUDA", "Go", "TypeScript", "Next.js"]
    summer_26 = "Google Summer of Code with ML4SCI"
```

<br/>

<div align="center">
<table>
<tr>
<td align="center" width="50%">




## What I'm Building Now

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  >  RL agents for Tetris: rendered pixels vs engineered state   │
│  >  TraceLens: finding out where a Linux process loses time     │
│  >  CUDA Optimization for both Options Pricing and PINNs        │
│  >  CSCI 2470 work at Brown: deep learning projects             │
│  >  LLM alpha crowding research                                 │
│  >  Java Trading Engine                                         │
│  >  Hieroglyph Segmentation for Brown's Digital Pyramids Project│
│  >  An Adaptive Data Structure Optimizer                        │
│  >  Finding new and interesting papers to replicate!            │
│  >  Trying to survive math & physics classes                    │
└─────────────────────────────────────────────────────────────────┘
```

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[SPINN: Ion Trap Shape Optimization](https://github.com/ML4SCI/SPINN)**
<br/><br/>
A summer spent trying to make a PINN redesign Paul trap electrodes. PINNs are notoriously finicky to differentiate real improvements from improvement achieved via cheating. The README should document how I dealt with that. Research is still ongoing!

`PINNs` `PDEs` `GSoC`

</td>
<td width="50%" valign="top">

**[TraceLens](https://github.com/georgezliao/eBPF-Agent)**
<br/><br/>
A Linux eBPF tool that shows how long syscalls take and how long threads wait for a CPU, per process. The latency histograms stay in the kernel, and individual calls are streamed for one process at a time.

`Go` `C` `eBPF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Fused CUDA for Higher-Order AD](https://github.com/georgezliao/Expanded-GPU-Optimization)**
<br/><br/>
Profiles the graph traversal, tensor materialization and kernel-launch costs of higher-order autodiff with Nsight Systems, then replaces them with a fused CUDA residual kernel.

`CUDA` `C++` `PyTorch`

</td>
<td width="50%" valign="top">

**[RL Robot Tetris](https://github.com/georgezliao/rl-robot-tetris)**
<br/><br/>
Compares agents that learn from rendered UI pixels with agents that get engineered state, along with reward shaping, action spaces, and search baselines like beam search and MCTS. Motivation is to learn more about RL environments and different reward systems.

`Python` `RL` `CNNs`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Gravitational Lensing PINNs](https://github.com/georgezliao/Gravitational-Lensing-PINNs)**
<br/><br/>
Physics-informed neural networks for gravitational lens mass reconstruction. My PHYS 2600 final project.

`Python` `PINNs` `Astrophysics`

</td>
<td width="50%" valign="top">

**[SkyPrint](https://github.com/georgezliao/SkyPrint2)**
<br/><br/>
Shows the climate impact of flights, including contrails, using CoCiP contrail modeling and an airline scoring system. [Try it live](https://www.skyprint.photo/).

`Next.js` `TypeScript` `Python`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[Java Trading Engine](https://github.com/georgezliao/Java-Trading-Engine)**
<br/><br/>
A limit order book and tail-latency harness in Java. An allocation-free hot path and a lock-free SPSC ring took p99 from 10.0 µs to 0.5 µs at 1M msg/s, and every variant has to produce the same output hash as the baseline.

`Java` `Low latency` `JMH`

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>
