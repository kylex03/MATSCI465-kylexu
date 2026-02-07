- This repository contains my Week 02 submission for MATSCI465.

- The workflow demonstrates 4D-STEM “virtual detectors,” where BF/ADF (and other detector geometries) are reconstructed **after** acquisition by integrating intensity over user-defined regions of the diffraction pattern.

- Checkpoints overlap so I just copy-pasted some functions I defined in earlier parts just for clarity.

## Contents
- `assignment_02.ipynb`: virtual detector framework, diffraction statistics (Itot/CoM/radial profiles), and an analysis pipeline.
- `assignment_02_output/figures/`: exported publication-quality figures (virtual BF/ADF + analysis plots).
- `assignment_02_output/data/raw/`: input dataset(s), including `Si-SiGe.dm4` (if included in repo per course rules).

## How to run locally
1. Activate the environment (`matsci465`).
2. Launch Jupyter:
   ```bash
   jupyter lab
