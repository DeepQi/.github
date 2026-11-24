# DeepQi (深气) — Autonomous Multi-Grid Deep Reinforcement Learning Go Engine

<p align="center">
  <strong>Bridging Classical Topological Theorems and Modern Deep Neural Networks across All Board Geometries (7x7 to 19x19)</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-10B%2F96F%20SE--ResNet-blue?style=flat-square" alt="Architecture" />
  <img src="https://img.shields.io/badge/Engine-Native%20Rust%20MCTS%20(PyO3)-orange?style=flat-square" alt="Rust MCTS" />
  <img src="https://img.shields.io/badge/Framework-Keras%203%20%7C%20TensorFlow-red?style=flat-square" alt="Keras 3" />
  <img src="https://img.shields.io/badge/Acceleration-mixed__float16%20%7C%20TF32-green?style=flat-square" alt="Acceleration" />
  <img src="https://img.shields.io/badge/License-Proprietary%20Research-lightgrey?style=flat-square" alt="License" />
</p>

---

## What is DeepQi?

**DeepQi (深气)** is an autonomous, multi-grid Deep Reinforcement Learning Go engine. 

### Origins: From Textbook to Autonomous Research
The project was originally sparked by the inspirational foundation of Max Pumperla and Kevin Ferguson's seminal book *„Deep Learning and the Game of Go“* (Manning Publications). What began as a hands-on exploration of the textbook's core principles has since grown far beyond pedagogical prototypes into an autonomous, state-of-the-art AI research platform: replacing early Python scripts with native Rust tree-batched MCTS, Keras 3 Tensor Core acceleration, multi-grid curriculum dynamics, and topological unconditional life guarantees.

While pioneering milestones like **AlphaGo Zero** and **Leela Zero** were fundamentally locked to fixed 19x19 grids, DeepQi establishes a unified **Multi-Grid Topological Paradigm**: A single, fully-convolutional neural network that natively learns, evaluates, and masters all board dimensions from fast 7x7 tactical skirmishes up to monumental 19x19 full-board battles—synthesizing modern auxiliary loss heads with exact topological theorems (David Benson's Unconditional Life).

```text
       Tactical Blitz             Meso-Scale Harmony             Monumental Macro-Go
    [ 7x7 ] ──► [ 9x9 ] ──► [ 11x11 ] ──► [ 13x13 ] ──► [ 15x15 ] ──► [ 17x17 ] ──► [ 19x19 ]
                                      ▲
                                      │ (Single Universal SE-ResNet Tower)
                           [ DeepQi Core Brain ]
```

---

## Key Scientific Breakthroughs

### 1. David Benson's Theorem (1976) meets Deep RL
Early AlphaGo Zero reproductions frequently suffered from *terminal blindness*—suicidal self-atari loops in unlosable endgames. DeepQi eliminates this by integrating **David B. Benson's mathematical Unconditional Life Algorithm** directly into the spatial perception tensor. Vital eye chambers and uncapturable chains are topologically guaranteed, yielding over **97% clean double-pass game completions** without endgame noise.

### 2. Empirical Edo-Period Te-ai Jubangos
DeepQi measures its progressive playing strength through historical **100-game Uchikomi handicap ladders** against certified reference engines (such as GNU Go 3.8 Level 0):
* **Radical Error-Variance Compression:** Across 9 full evolution cycles, DeepQi's average loss margin dropped by **-62.2% on 9x9** (from 30.7 points down to 11.6 points) and by **-76.1% on 7x7** (from 28.7 points down to 6.8 points).
* **Handicap Perfection:** Achieving **100.0% winrates at 2 stones on 7x7** and **94.4% at 4 stones on 9x9** (+54.2% higher average score lead).

### 3. Harmonic Curriculum & Experience Washout
To prevent format shock across vastly different grid sizes, training follows an autonomous **10-step zigzag curriculum schedule**. Saturated first-in-first-out (FIFO) replay buffers continuously wash out obsolete game data with recency weighting, ensuring that gradient updates are driven by high-quality, mature play.

---

## Current Operational State

As of the latest evolution milestone (**Cycle 60 / Master G740**):

* **Neural Backbone:** 10-Block / 96-Filter Squeeze-and-Excitation Residual Network (SE-ResNet) evaluating a unified 16-plane topological perception matrix.
* **Quad-Head Multitask Output:** Simultaneous inference of Move Policy (99.0% Top-5 move intuition), Win Probability (Value MSE 0.6945), Territory Ownership, and End-Game Score Margin.
* **Multi-Format Replay Reservoir:** Fully saturated 420,000-position memory across all 7 board formats (60,000 positions each from 7x7 to 19x19) operating with 100% native representation purity.
* **High-Speed Search Engine:** Concurrency-optimized native Rust MCTS core (via PyO3) with tree-batched leaf evaluations and dynamic topological eye protection.
* **Empirical Playing Strength:** Proven solid double-digit kyu (DDK) capability verified through continuous 100-game Edo-period handicap matches against certified reference engines.

---

## Active Research Frontiers

```text
[ Stage 1: Hardware Acceleration ] ──► COMPLETED (v0.56.1)
  * Keras 3 mixed_float16 & TensorFloat-32 (TF32) on NVIDIA Tensor Cores (1.94x speedup).
  * Strict FP32 numerical invariance on Policy, Value, Ownership, and Score heads.

[ Stage 2: Harmonized 20D Benson Matrix ] ──► ACTIVE
  * Expansion to 20-plane tensor (5 blocks of 4 channels) for perfect Tensor Core alignment.
  * Channel 7: Unconditional Territory Theorem.
  * Block 5: Cybernetic Memory (Previous Policy Intent & Recurrent Spatial Memory).
  * Mathematically proven Net2Net Zero-Init: 0.0% cold-start Elo degradation.

[ Stage 3: BoTNet 12B/128F Hybrid Architecture ] ──► ON THE HORIZON
  * 12 Residual Blocks / 128 Filters (~3.6M parameters).
  * 2 Axial Transformer blocks via ReZero coupling (alpha = 0.0).
  * Full-board ladder reading (Shicho) in O(N) complexity without search tree explosion.
```

---

## Deployment Roadmap

DeepQi is currently an internal research laboratory. A standalone, high-performance desktop release (**`DeepQi.exe`**) featuring:
* Full **GTP 2.0 (Go Text Protocol)** support for graphical frontends (Sabaki, Lizzie, KaTrain),
* Native Multi-Grid Board Support (auto-sensing 7x7 to 19x19),
* Tree-Batched Native Rust MCTS Engine,

is planned for a future release.

---

<p align="center">
  <em>DeepQi Research Project. All rights reserved.</em>
</p>
