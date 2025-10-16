# Black Hole Equation: Quantum–Gravitational Framework

This repository contains GNU Octave scripts and pre-generated figures for the paper:

**"The Black Hole Equation: Toward a Unified Quantum Model of Gravity and Curvature"**  
DOI: [10.5281/zenodo.17366620](https://doi.org/10.5281/zenodo.17366620)

The project demonstrates the quantum structure, self-gravity feedback, and spin effects in black holes using the **Black Hole Equation (BHE)**.

---
Black_Hole_Equation/
│
├── fig1.png # Quantum mass distribution |Ψ(r)|^2
├── fig2.png # Self-gravity feedback potential
├── fig3.png # Spin-dependent quantum distribution
├── wavefunction.m # Octave script for Fig. 1
├── self_gravity.m # Octave script for Fig. 2
├── spin_effect.m # Octave script for Fig. 3
├── README.md # This file
└── LICENSE # License file
---

## Requirements

- [GNU Octave](https://www.gnu.org/software/octave/) (version ≥ 6 recommended)
- Optional: LaTeX for integrating figures into your manuscript

---

## Usage

### 1. Quantum Mass Distribution
wavefunction.m
Generates fig1.png showing the probability density |Ψ(r)|².

2. Nonlinear Self-Gravity Feedback
octave
Copy code
self_gravity.m
Generates fig2.png, visualizing the self-gravity term of the BHE.

3. Spin Dependence
octave
Copy code
spin_effect.m
Generates fig3.png showing spin coupling effects on the quantum black hole core.

All scripts normalize the wavefunctions and use default parameters as presented in the paper. You can modify parameters like sigma, L, G, or epsilon for experimentation.

Citation
If you use these scripts or figures, please cite the paper:

Koranat C., The Black Hole Equation: Toward a Unified Quantum Model of Gravity and Curvature, Zenodo, DOI: 10.5281/zenodo.17366620

License
This repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to share and adapt the work as long as proper credit is given.
This repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to share and adapt the work as long as proper credit is given.
