---
layout: default
title: Quantum Controller
parent: Quantum Hardware
grand_parent: Hardware Related Terms
nav_order: 1
---

# Quantum Controller
{: .fs-9 }
Classical hardware close to the quantum computer controlling the execution of quantum programs on the quantum computer.
{: .fs-6 .fw-300 }

Classical
{: .label }

Quantum
{: .label .label-green}

## Full Definition

The quantum controller is usually a microcontroller or FPGA that controls the execution of quantum programs by triggering the waveform generators acting on the qubits. Research is done to execute limited classical code on the quantum controller in the coherence time of the qubits, enabling [Dynamic Lifting].

[Dynamic Lifting]: {{ site.baseurl }} {% link glossary/hardware-related/communication/dynamic-lifting.md %}