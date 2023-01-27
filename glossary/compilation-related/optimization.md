---
layout: default
title: Optimization
parent: Compilation Related Terms
nav_order: 4
---

# Optimization
{: .fs-9 }
Improving a quantum circuit with respect to certain metrics (often depth or gate count) without altering the observable result of the circuit when executed without error.<sup>[1](#note_1)</sup>
{: .fs-6 .fw-300 }

Quantum
{: .label .label-green}

## Full Definition
Optimization can work on the whole circuit or on small parts of it. A prominent example are very local optimizations, so called "peephole optimizations". For example:
- *Gate cancellation* (two consecutive gates on the same qubit, one of which is the inverse of the other, can be removed)
- *Rotation folding* (two successive rotations on the same qubit and axis of rotation can be combined into a single rotation by adding up their angles)

## Footnotes
1. A lower gate count leads to less errors introduced by gates, hence the results on real hardware can differ <a href="#note_1"></a>