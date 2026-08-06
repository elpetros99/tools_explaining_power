# NTK Analysis of Physics-Informed Surrogates for Power-System Dynamics

This repository contains the code and supplementary material for the paper
**“Tools to Explain Neural Networks for Power System Dynamics.”**

The work uses Neural Tangent Kernel (NTK) analysis to study how neural-network
architecture, physical stiffness, timescale separation, and loss weighting
affect the training of physics-informed machine-learning surrogates for
power-system dynamics. The code will be uploaded upon acceptance.

The repository includes:

- implementations of vanilla PINNs, KANs, and ActNet;
- synchronous-machine, modified SMIB, and grid-following inverter models;
- scripts for training and evaluating the surrogate models;
- NTK spectrum and gradient-imbalance analysis;
- adaptive NTK-based loss weighting;
- scripts used to reproduce the figures and tables in the paper;
- model parameters, experiment configurations, and evaluation settings;
- the supplementary appendix containing additional model equations,
  parameter values, implementation details, and results.

The main goal is to support reproducibility and provide practical tools for
understanding why physics-informed neural surrogates succeed or fail when
learning stiff and multi-timescale power-system dynamics.


Change the commands to match your actual scripts.

## Citation section for the README

```markdown
## Citation

Please cite the accompanying paper when using this repository:

```bibtex
@article{ellinas2026tools,
  title   = {Tools to Explain Neural Networks for Power System Dynamics},
  author  = {Ellinas, Petros and Vorwerk, Johanna and
             Chatzivasileiadis, Spyros},
  journal = {To appear},
  year    = {2026}
}
