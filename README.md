# Mehdi Jenab

Research scientist working at the intersection of **HPC**, **quantum chemistry**, **plasma physics**, and **AI-assisted scientific software development**. This page curates the projects I publish publicly — small, focused, and built to be reused or learned from.

## Interests

- Quantum algorithms, error correction, and quantum machine learning
- Plasma kinetic theory and numerical methods (Vlasov–Poisson solvers, BGK modes, electron holes, solitons)
- Computational chemistry and electronic structure (CCSD, VQE for molecules)
- AI-assisted scientific software — multi-agent workflows, reusable LLM skills
- High-performance computing in C++ and Python

## Quantum computing

- **[quantum-algorithm-toolkit](https://github.com/MehdiJenab/quantum-algorithm-toolkit)** — Modular Qiskit implementations of fundamental quantum algorithms: Grover, QPE, Deutsch–Jozsa, Bernstein–Vazirani. Tests and Jupyter demos included.
- **[quantum-error-correction](https://github.com/MehdiJenab/quantum-error-correction)** — Surface-code QEC simulator built from scratch: lattice geometry, depolarizing noise, syndrome extraction, MWPM decoding, threshold analysis.
- **[quantum-error-mitigation](https://github.com/MehdiJenab/quantum-error-mitigation)** — Toolkit for quantum error mitigation on NISQ devices: Zero-Noise Extrapolation (ZNE) and Measurement Error Mitigation, with a unified pipeline and a VQE demo for the H₂ molecule.
- **[pennylane-qml-vqc](https://github.com/MehdiJenab/pennylane-qml-vqc)** — Hybrid variational quantum classifier built with PennyLane: multiple feature maps and ansätze, classical baselines, and decision-boundary visualizations.
- **[elin-gate-toolkit](https://github.com/MehdiJenab/elin-gate-toolkit)** — Qiskit primitive and density-matrix simulator for the Elin gate, a temporal-isolation operation from Jenab's lab-space quantum mechanics.
- **[quantum](https://github.com/MehdiJenab/quantum)** — Notes and exploratory writing on quantum mechanics, quantum computing, and quantum cryptography.

## Plasma physics & kinetic theory

- **[vlasov-poisson-solver](https://github.com/MehdiJenab/vlasov-poisson-solver)** — Phase-point kinetic solver for nonlinear plasma waves. Used in 15+ publications on BGK modes, electron holes, and soliton dynamics. C++ with MPI parallelization, JSON config, and HDF5 output.
- **[vps-modern](https://github.com/MehdiJenab/vps-modern)** — Modern C++23 Vlasov–Poisson solver using the method of characteristics. Supports Landau damping, BGK modes, electron holes, and multi-species plasmas. OpenMP parallel with planned MPI.
- **[stencil-poisson-solver](https://github.com/MehdiJenab/stencil-poisson-solver)** — High-order finite-difference tools for 1D Poisson problems. Builds stencil matrices from configs, optionally enforces periodic/zero-mean fixes, and exports inverse operators for fast solves.
- **[elin-df](https://github.com/MehdiJenab/elin-df)** — Python implementation of the Elin Distribution Function framework for studying nonlinear electrostatic structures (electron and ion holes, solitons) in plasmas.

## Computational chemistry

- **[ccsd-hehp-cpp](https://github.com/MehdiJenab/ccsd-hehp-cpp)** — C++ implementation of Coupled Cluster Singles and Doubles (CCSD) for the HeH⁺ molecule.

## Tooling / infrastructure

- **[my-skills](https://github.com/MehdiJenab/my-skills)** — Reusable [Claude Code](https://claude.com/claude-code) skills I share publicly. Currently: `teach-me` (interactive paper / topic tutor), with more to come.
- **[claude-multi-agent-framework](https://github.com/MehdiJenab/claude-multi-agent-framework)** — Sidecar workflow templates for orchestrating multiple Claude agents on long-running tasks (code development, paper writing, clean-code refactoring).

## Contact

- LinkedIn: [linkedin.com/in/mehdi-jenab-phd](https://www.linkedin.com/in/mehdi-jenab-phd/)
