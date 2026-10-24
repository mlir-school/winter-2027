---
layout: single
title: "Topics"
permalink: /expert-topics/
classes: wide
---

**Programme coordination:** P. Sadayappan & Kunwar Grover.

The week is organised around a few **hot topics**. Each topic is led by an animator who invites speakers and contributors. Days mix short talks with extended working-group / coding time so participants can dig into existing dialects with their authors.

<div class="topic-card topic-backends">
<h2 id="backends">Backends</h2>
<p><strong>Leads:</strong> Ayal Zaks</p>
<p>Today, most MLIR-based compilation pipelines still rely on the traditional LLVM backend for the final lowering stages: once lowered to LLVM IR and handed off to <code>opt</code> and <code>llc</code> for instruction selection, register allocation, and low-level optimizations, the benefits of MLIR’s structured abstractions are lost. However, the landscape is shifting as backend infrastructure is increasingly extended directly within MLIR—opening the door to composable, retargetable passes that preserve high-level semantics. This track explores how far code generation can be pushed inside MLIR itself, covering declarative instruction selection, customizable register allocation, low-level dialects and scheduling languages, and practical strategies for migrating non-CPU/non-GPU accelerator middle- and back-ends from LLVM to MLIR.</p>
</div>

<div class="topic-card topic-hpc">
<h2 id="hpc">HPC</h2>
<p><strong>Leads:</strong> William S. Moses</p>
<p>High-performance computing poses unique compilation challenges around parallelism, memory hierarchies, distributed execution, and legacy scientific codebases. MLIR provides building blocks for addressing these challenges, including the <code>affine</code>, <code>scf</code>, <code>linalg</code>, <code>vector</code>, <code>memref</code>, <code>gpu</code>, and <code>omp</code> dialects for loop transformations, stencil computations, data-layout optimization, vectorization, and accelerator offloading. The FIR/HLFIR-based Flang frontend also brings Fortran into the MLIR ecosystem, offering opportunities to optimize array-oriented scientific code while preserving high-level semantics. This track focuses on how MLIR dialects and transformations can represent and optimize HPC workloads, from polyhedral and loop-level optimizations to GPU/accelerator offloading and integration with existing HPC programming models. Open challenges include performance portability across heterogeneous architectures, optimization of irregular and distributed computations, effective cost models and autotuning, and the preservation of numerical accuracy and reproducibility.</p>
</div>

<div class="topic-card topic-frontends">
<h2 id="front-ends">Front-ends</h2>
<p><strong>Leads:</strong> Alex Zinenko</p>
<p>A growing set of front-ends now target MLIR directly from C/C++, Fortran, Python, and domain-specific languages. This track brings together authors and users of tools such as ClangIR (CIR), Polygeist, Reactant, and other entry points into the ecosystem to discuss high-level AST lowering, preserving source-level semantics, and sharing reusable abstractions across languages.</p>
</div>

<div class="topic-card topic-formal">
<h2 id="formal-methods--ir">Formal methods &amp; IR</h2>
<p><strong>Leads:</strong> Tobias Grosser</p>
<p>MLIR’s extensible, multi-dialect architecture creates opportunities to integrate formal methods into compiler design, from precise IR semantics and verified transformations to translation validation and synthesis of analyses and optimizations. Topics include declarative IR definitions such as IRDL and xDSL, equality saturation and e-graphs, and connections with functional and alternative compilation models. Open challenges include scaling verification to real-world compiler infrastructures, reducing reliance on hand-written optimisation logic, and bridging formal guarantees with data-driven optimisation and practical engineering constraints. A central question is how to make semantics-driven development and formal methods effective in everyday compiler development, while preserving performance, extensibility, and the collaborative workflows of the LLVM and MLIR communities.</p>
</div>

---

The detailed timetable is on the [Program](/program/) page.
