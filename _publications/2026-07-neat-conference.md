---
title: "NEAT: A Neutral-Atom Transpiler for Joint Mapping and Scheduling of Syndrome Extraction Circuits"
collection: publications
category: conferences
permalink: /publication/2026-07-neat-conference

excerpt: 'This paper is about syndrome extraction circuits compilation.'
date: 2026-07-01
venue: 'The Chips to Systems Conference (DAC 2026)'
---
## Abstract

Quantum Error Correction (QEC) demands efficient implementation of syndrome extraction circuits. However, existing compilers for neutral-atom processors largely miss the opportunity to co-optimize these circuits by exploiting both the structural properties of Quantum Error-Correcting Codes (QECCs) and the physical constraints of neutral-atom architectures. In this work, we introduce **NEAT**, an SMT-based compiler that jointly optimizes qubit mapping and syndrome extraction scheduling for a broad class of stabilizer-based QECCs, achieving depth-optimal execution with minimal shuttling overhead on neutral-atom platforms. Across a wide range of QECCs, NEAT consistently achieves near-optimal circuit depth and reduces atom movement by **3x-30x** compared the baseline compiler Enola. Logical-level simulations further demonstrate **2x-20x** lower logical error rates under realistic hardware noise. A hierarchical symmetry-breaking formulation and relaxed parallel-motion constraints substantially improve solver scalability, yielding up to **100x** speedup in compilation time. Together, these results show that NEAT produces depth-optimal, movement-efficient, and logically robust syndrome extraction schedules, while scaling effectively to large QECCs on neutral-atom hardware.
