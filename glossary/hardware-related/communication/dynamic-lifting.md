---
layout: default
title: Dynamic Lifting
parent: Communication
grand_parent: Hardware Related Terms
nav_order: 1
---

# Dynamic Lifting
{: .fs-9 }
Dynamic Lifting is the process of performing classical calculations based on quantum measurement results.
{: .fs-6 .fw-300 }

Quantum
{: .label .label-green }

## Full Definition
Dynamic lifting was originally termed by quipper as the conversion from measurement results (bit) to classical value (bool) <sup>[1](#src_1)<sup>.
During dynamic lifting, the quantum operations are (partially) suspended to execute classical operations, which govern the future circuit execution. 
The classical execution has to complete during the coherence time.
On most platforms, sending information over a bus would be intractable and therefore requires execution on the controller.
<!-- ## Examples -->

## Synonyms

- Real-Time Feedback
- Feedforward
- Dynamic circuits
- In-between measurements



## Related Terms

- [Coherence Time]

## Sources
1. Alexander S. Green, Peter LeFanu Lumsdaine, Neil J. Ross, Peter Selinger, and Benoît Valiron. 2013. Quipper: a scalable quantum programming language. SIGPLAN Not. 48, 6 (June 2013), 333–342. [doi](https://doi.org/10.1145/2499370.2462177)<a href="#src_1"></a>

[Coherence Time]: {{ site.baseurl }} {% link glossary/hardware-related/coherence-time.md %}

