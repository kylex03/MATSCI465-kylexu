# MATSCI465 — HW1

- This repository contains my HW1 submission for MATSCI465 as of 1/12/2026
- The class website is https://github.com/NU-MSE-LECTURES/465-WINTER2026

## Contents
- `assignment_01_setup.ipynb`: Completed HW1 setup notebook (environment checks, imports, image loading/visualization, basic statistics and histogram).
- `environment.yml`: Conda environment export for the `matsci465` environment (exported with `--no-builds`).
- `assignment_01_output/data/raw` includes the example EM image file used in `assignment_01_setup.ipynb`.
## How to run locally
1. Create the conda environment:
   ```bash
   conda env create -f environment.yml
2. Activate the environment:
   ```bash
   conda activate matsci465
3. Launch JupyterLab:
   ```bash
   jupyter lab
4. Open `assignment_01_setup.ipynb` and run cells from top to bottom. Double check the directory of the EM image file when running locally.
