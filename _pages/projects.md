---
layout: page
title: Projects
permalink: /projects/
description: Open source tools and software for Quantum Chemistry.
nav: true
order: 2
---

My technical work focuses on building robust Python/Fortran tools that bridge the gap between theoretical models and practical implementation.

### Quantum Software

#### [Active Space UCC & Resource Estimation]
* **Stack:** Python, Qiskit, PySCF
* **Description:** Developed novel Active Space Unitary Coupled Cluster (UCC) methods to simulate molecular systems. [cite_start]This work is critical for reducing the qubit and gate count required for near-term quantum chemistry[cite: 17].
* [cite_start]**Impact:** Used to provide critical resource benchmarks for simulating biology on future fault-tolerant hardware in collaboration with NASA[cite: 18].

#### [UCCSD(4)]
* **Stack:** Python, NumPy
* **Link:** [github.com/prateekvaish](https://github.com/prateekvaish)
* [cite_start]**Description:** Implementation of Unitary Coupled Cluster Singles and Doubles for classical hardware benchmarks[cite: 72]. Used to validate quantum results against classical limits.

### Machine Learning & Dynamics

#### [FT-RHF (Finite-Temperature Restricted Hartree-Fock)]
* **Stack:** Python, Github
* **Link:** [github.com/prateekvaish/FT-RHF](https://github.com/prateekvaish/FT-RHF)
* [cite_start]**Description:** A custom code for Finite-Temperature RHF calculations[cite: 72]. Finite temperature methods are essential for capturing the realistic behavior of biological systems in pharma applications.

#### [Scalable Gaussian Process Regression]
* **Stack:** Python, Fortran90
* [cite_start]**Description:** Developed a numpy variant of GPR using CUR decomposition for approximate inverse covariance matrices[cite: 30].
* [cite_start]**Application:** Enabled the fitting of Formaldehyde Potential Energy Surfaces (PES) and resolved numerical stability issues for $$He-F_{2}$$ systems[cite: 36].