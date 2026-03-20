# Structural Accessibility Boundaries and Recoverability in a Minimal H–O Redox Network Model
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19123634.svg)](https://doi.org/10.5281/zenodo.19123634)

This repository contains the full computational reproduction of a minimal H–O redox network model exploring structural accessibility and recoverability.

---

## Overview

This work investigates whether recoverability can be understood as a **structural property of a state-space network**, rather than a purely dynamical one.

Instead of focusing on concentrations or kinetics, the model evaluates whether states remain accessible to a reference equilibrium under bounded transition cost.

---

## Key Concept

A node is considered **recoverable** if its minimum weighted distance to a defined core set is below a threshold.

The results suggest:

- A **discrete accessibility boundary**
- **Robustness** under local perturbations
- **Loss of invariance** under global reweighting
- A **bottleneck-controlled mechanism**
- A **critical transition** driven by the O₃ → O₂ pathway

---

## Repository Contents

- `structural_accessibility_full_reproduction_FINAL.ipynb`  
  Full reproducible notebook  

- `Structural Accessibility Boundaries and Recoverability in a Minimal H–O Redox Network Model.pdf`  
  Companion paper  

- `image/`  
  Figures generated from the model  

---

## How to Run

Install dependencies:

`pip install networkx numpy matplotlib`

Launch Jupyter:

`jupyter notebook`

Open structural_accessibility_full_reproduction_FINAL.ipynb and click Run All.

⸻

## Reproducibility

	•	No external data required
	•	Fully deterministic (fixed seeds)
	•	Entire pipeline contained in a single notebook

⸻

## Related Work

This work complements a prior dynamical model on rate-dependent recoverability.

- DOI version: https://doi.org/10.5281/zenodo.19069265  
- Code repository: https://github.com/jaimeojse-collab/oxygen-regime-boundary-minimal

⸻

## Note

This model is presented as a testable structural hypothesis.
Results may change under modifications to network topology or transition weights.

⸻

## Citation

If you use this work, please cite:

Ojeda, J. (2026).  
Structural Accessibility Boundaries and Recoverability in a Minimal H–O Redox Network Model.  
Zenodo. https://doi.org/10.5281/zenodo.19123634

⸻

## License

MIT License
