---
layout: default
title: Scheduling
parent: Runtime Related Terms
nav_order: 5
---

# Scheduling
{: .fs-9 }
Scheduling refers to the task of distributing restricted resources (CPU, QPU,...) between different parties (processes, users). 
{: .fs-6 .fw-300 }

Classical
{: .label }

Quantum
{: .label .label-green}

## Full Definition
The execution queue of jobs is called a **schedule**.
Scheduling can occur on different levels:
- On a job level user access to computing resources is managed.
- On a process level, shared resources between processes are managed. 
- In quantum computing, scheduling can be applied on a circuit level, ordering the application of gates. 

Scheduling is usually handled by the runtime environment. \newline \emph{Related Terms} Runtime Environment

## Examples

- [Slurm](https://slurm.schedmd.com/overview.html), open source scheduler

<!-- ## Synonyms

- -->

## Related Terms

- [Runtime Environment]

<!--## Sources
1.  -->

[Runtime Environment]: {{ site.baseurl }}{% link glossary/runtime_related/runtime_environment.md %}
