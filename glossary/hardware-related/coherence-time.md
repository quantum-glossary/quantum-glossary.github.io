---
layout: default
title: Coherence Time
parent: Hardware Related Terms
nav_order: 2
use_math: true
---

# Coherence Time
{: .fs-9 }
Figuratively, the time it takes for a quantum state to be subject to energy decay or dephasing, limits the operation fidelity on the qudits involved.
{: .fs-6 .fw-300 }

Quantum
{: .label .label-green}

## Full Definition

Decoherence is a specific form of noise.
The decoherence time $$t_Q$$ is the time in which a quantum system loses its *coherence*<sup>[1](#src_1)</sup>.

## Examples

In nuclear spin systems there are two major sources of decoherence<sup>[1](#src_1)</sup>:
- \\(T_1\\) spin-lattice/longitudinal relaxation
- \\(T_2\\) spin-spin/transverse relaxation

Both are associated with a different point in time \\(t\\).
At \\(T_1=t\\), the net magnetization of a physical system is at 63% of its maximum value.
At \\(T_2=t\\), the transverse magnetization of a physical system is at 37% of its initial value.
For a detailed explanation see: [T1](https://mriquestions.com/what-is-t1.html) and [T2](https://mriquestions.com/what-is-t2.html)

Figuratively speaking \\(T_1\\)-time,  describes the probability of a qubit still being in \\(\ket{1}\\) after the time \\(t\\) and the \\(T_2\\)-time describes the probability of a qubit still being in \\(\ket{+}\\) after the time \\(t\\).
<!-- ## Synonyms -->


<!-- ## Related Terms

-->
## Sources
1. Nielsen, Michael A., and Isaac Chuang. 2002 Quantum computation and quantum information.<a href="#src_1"></a>


