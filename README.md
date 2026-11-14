# Washington, D.C. Bike Rental Analysis

An interactive Streamlit dashboard for exploring a bike-rental training dataset. The repository contains the original analysis script and the `train.csv` dataset.

## What it includes

- Dataset preview and interactive sidebar filtering
- Numeric range filters, date filters, and categorical filters
- Summary metrics and descriptive statistics
- Histograms, scatter plots, category counts, and a correlation heatmap
- Interactive Plotly charts

## Tech stack

Python, Streamlit, pandas, Plotly, Matplotlib, and Seaborn.

## Run locally

```bash
git clone https://github.com/singhaarvi728/washington-D.C-Bike-Renatl.git
cd washington-D.C-Bike-Renatl
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows PowerShell:
# .venv\Scripts\Activate.ps1
pip install -r requirements.txt
streamlit run DVAssignment3.3.py
```

The app expects `train.csv` in the project root; that file is included in this repository.

## Repository contents

| File | Purpose |
|---|---|
| `DVAssignment3.3.py` | Streamlit dashboard and analysis |
| `train.csv` | Bike rental dataset |
| `requirements.txt` | Python dependencies |

## Notes

This repository preserves the project files currently available in the GitHub account. The README documents the existing implementation; it does not claim to be a byte-for-byte recovery of files from a previous computer. Dataset interpretation and conclusions should be based on the supplied CSV and verified by rerunning the analysis.

## Future improvements

- Add data validation and explicit schema checks
- Add time-series demand analysis and peak-hour comparisons
- Add automated tests for filtering and aggregation logic
- Separate analysis, visualisation, and UI code into modules
