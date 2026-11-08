# INCOIS Internship Projects

A curated collection of Jupyter notebooks from my internship work at INCOIS. 

project title :- Development of a Machine Learning-Based, Long-Term (1998-2025) Gap-Free Monthly Surface Chlorophyll-a Dataset for the North Indian Ocean

The notebooks cover ocean data preparation, long-term prediction and trend analysis, and machine-learning workflows for the Bay of Bengal, Eastern Arabian Sea, and Western Arabian Sea.

The project was conducted as part of the IASc–INSA–NASI Summer Research Fellowship Programme 2026 at Indian National Centre for Ocean Information Services (INCOIS), Ministry of Earth Sciences, Hyderabad.

## Repository contents

- **`data_preparation/`** — Notebook for deriving ocean dynamic variables.
- **`long_term_predictions/`** — Long-term prediction notebook covering 1998–2025.
- **`long_term_trend_analysis/`** — LightGBM trend-analysis notebooks. The analysis includes both annual mean and seasonal mean trend comparisons using the OC-CCI observations, the ACRI gap-filled dataset, and the LightGBMpredicted data for the Bay of Bengal, Eastern Arabian Sea, and Western Arabian Sea regions seperately.
- **`ML_Models/`** — LightGBM and XGBoost notebooks organized by region, with separate folders for training, tuning, and predictions where applicable.

## Folder structure

```text
.
├── data_preparation/
├── long_term_predictions/
├── long_term_trend_analysis/
└── ML_Models/
    ├── BOB/
    │   ├── LightGBM/
    │   └── XGBoost/
    ├── Eastern_AS/
    │   ├── LightGBM/
    │   └── XGBoost/
    └── Western_AS/
        ├── LightGBM/
        └── XGBoost/
```

`BOB` means Bay of Bengal. `Eastern_AS` and `Western_AS` refer to the Eastern and Western Arabian Sea.

## Using the notebooks

1. Open a notebook in Jupyter Notebook, JupyterLab, or a compatible editor.
2. Check the notebook’s import cells and install any required Python packages.
3. Update file paths to match the location of your data.
4. Run the cells in order.

The notebooks are organized by task and region. Data files and the Python environment used to run them may not be included, so some setup may be needed.

## Notes

This repository contains selected internship code. Please follow the applicable data-sharing and attribution requirements when reusing the notebooks or related research data.
