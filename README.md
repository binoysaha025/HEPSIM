# ML4SCI HEPSIM GSoC 2026 — Evaluation Task

**Author:** Binoy Saha | University of Texas at Arlington  
**Program:** Google Summer of Code 2026 — ML4SCI HEPSIM

## Overview
Full evaluation task solution for the ML4SCI HEPSIM GSoC 2026 projects:
- Symbolic Regression for Observable Event-Level Reweighting
- ML-Based Simulation Bias Analysis (Pythia vs Herwig)

## What's in the notebook
- **Part A** — Data loading and exploration of the Pythia8 Quark/Gluon Jets dataset (200k jets)
- **Part B** — Jet observable computation: invariant mass, jet width, pT dispersion
- **Part C** — Lorentz boost to jet rest frame with numerical verification
- **Part D** — Neural network classifier (PyTorch) achieving ~79% test accuracy with ROC curve, confusion matrix, and permutation feature importance

## Dataset
Pythia8 Quark and Gluon Jets — Zenodo (doi:10.5281/zenodo.3164691)  
Not included in repo due to file size. Download directly from Zenodo.

## Requirements
```
pip install numpy matplotlib scikit-learn torch jupyter
```
