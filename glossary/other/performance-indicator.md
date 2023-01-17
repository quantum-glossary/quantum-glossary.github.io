---
layout: default
title: Performance Indicator
parent: Other
nav_order: 2
---

# Performance Indicator
{: .fs-9 }
Performance Indicators measure the result of an optimization technique (as a metric) under specific aspects.
{: .fs-6 .fw-300 }

Classical
{: .label }

Quantum
{: .label .label-green }

<!-- ## Full Definition

tbd. -->

## Examples

In quantum computing the most commonly used indicators are:
-  **Fidelity**<a href="fidelity"></a>: A measure of closeness of two quantum states. Used to compare noiseless simulation to noisy physical execution. **Gate Fidelity** is the fidelity induced by a single quantum gate.
- Duration: Overall execution time of a quantum operation, usually related to the coherence time.
- Gate-Depth: The maximum number of (multi-qudit) gates on a qudit. Most commonly as T-Gate-Depth, which only counts a specific set of gates.
- Noise Resilience: A measure of how well a circuit performs on varying levels of noise. No concrete metric exists yet.

## Synonyms

- Metric

## Related Terms
- [Coherence Time]
<!--## Sources
1.  -->

[Coherence Time]: {{ site.baseurl }} {% link glossary/hardware-related/coherence-time.md %}
