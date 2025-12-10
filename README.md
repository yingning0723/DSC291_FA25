# DSC 291 (FA25) — Final Project

This repository contains my final project work for **DSC 291 (Fall 2025)**.

## Contents

- `final_proj.ipynb` — Main notebook (data loading, analysis, plots, and results).
- `data/` — Input CSV files used by the notebook:
  - `DetectorA.csv`
  - `DetectorB.csv`
  - `DetectorC.csv`
  - `DetectorTarget.csv`

## How to Run

### Option 1: Run on DataHub / Jupyter
1. Open `final_proj.ipynb`
2. Run cells from top to bottom

### Option 2: Run locally
```bash
# create environment (example with conda)
conda create -n dsc291 python=3.10 -y
conda activate dsc291

# install common dependencies
pip install numpy pandas matplotlib scipy scikit-learn jupyter
jupyter notebook
