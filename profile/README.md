# OpenLithoHub

**Open-source differentiable simulation and computational physics tools for inverse design, manufacturability, and AI research.**

We build PyTorch-native, fully differentiable solvers across the spectrum of physical design problems — bringing gradient-based optimization and machine learning to domains previously locked behind black-box simulation tools.

---

## Projects

### [OpenLithoHub](https://github.com/OpenLithoHub/OpenLithoHub) — Computational Lithography
Unified benchmarking and workflow toolkit for advanced EUV/curvilinear mask processes. Differentiable ILT/OPC optimization, manufacturability metrics (MRC/DRC, EUV stochastics, shot count), and a full pipeline from PyTorch tensors to OASIS.MBW mask writer format.

### [DiffNano](https://github.com/OpenLithoHub/DiffNano) — Differentiable Nanophotonics
PyTorch-native differentiable FDTD and RCWA solvers for inverse design of metasurfaces, metalenses, photonic crystals, and waveguide components. Bridges the gap between electromagnetic simulation and gradient-based optimization — no adjoint equations required.

### [DiffCFD](https://github.com/OpenLithoHub/DiffCFD) — Differentiable Fluid Dynamics
Lightweight differentiable Navier-Stokes and heat transfer solver for shape optimization, reinforcement learning environments, and neural surrogate training. Designed as a differentiable co-pilot to production CFD codes (OpenFOAM, SU2), not a replacement.

### [sCO₂-TMSR-Toolkit](https://github.com/OpenLithoHub/sCO2-TMSR-Toolkit) — Supercritical CO₂ Cycle Modeling
Open-source thermal-hydraulic modeling toolkit for supercritical CO₂ Brayton cycles in advanced fission and fusion reactors. CFD-ROM-FMU pipeline for system-level power cycle optimization.

---

## Shared Philosophy

All four projects address a common challenge: **physical systems that are expensive to simulate and impossible to differentiate with existing tools**. Each project provides:

- A differentiable PyTorch-native solver (gradients through physics)
- Standardized benchmark suites for reproducible comparison
- Fabrication / process-aware constraints baked into the optimization loop
- Open datasets and leaderboards for community progress tracking

---

## Get Started

```bash
pip install openlithohub   # Computational lithography
pip install diffnano        # Nanophotonics inverse design  (coming soon)
pip install diffcfd         # Differentiable CFD            (coming soon)
```

---

## License

All projects are released under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) unless otherwise noted.
