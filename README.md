![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter) ![License](https://img.shields.io/badge/License-MIT-green)

# Credit Risk Analytics | NPA Prediction & Modelling

> Exploratory data analysis project.

**Author:** Pitambar  &nbsp;|&nbsp; **Dataset:** Finsight Bank (CDAC - Bank)

---

## Overview

This project performs a complete exploratory data analysis (EDA) on the Finsight Bank (CDAC - Bank) dataset. It covers data acquisition, cleaning, univariate and multivariate analysis, feature engineering, and regression modelling — following a structured, reproducible workflow in Jupyter Notebook.

## Project structure

```
credit-risk-analytics-npa-prediction-modelling/
├── notebook.ipynb          # Main analysis notebook
├── README.md               # This file
├── requirements.txt        # Python dependencies
├── data/                   # Data files (not tracked by Git)
│   └── README.md           # Instructions to download data
└── outputs/                # Saved charts and tables
```

## Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/credit-risk-analytics-npa-prediction-modelling.git
cd credit-risk-analytics-npa-prediction-modelling

# 2. Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

**Requirements:** Python 3.10+ · pandas | numpy | matplotlib | seaborn | scipy | statsmodels |  sklearn 

## Usage

1. Place the dataset CSV files in the `data/` folder.
2. Open `notebook.ipynb` in Jupyter.
3. Update the `DATA_DIR` variable in the first cell to point to your `data/` folder.
4. Run all cells: **Kernel → Restart & Run All**.

## Key findings

Portfolio default rate: 3.88%. EMI bounce count is the strongest predictor (r=0.83).
Grade G loans default at 3.7 the rate of grade A

See the notebook for full charts, statistical tests, and model diagnostics.

## Notebook sections

| Section | Description |
|---------|-------------|
| Q1 · Data gathering & cleaning | Load 9 CSV files, join on `loan_id`, fix 8 data quality issues |
| Q2 · EDA (12 charts) | Univariate, bivariate, temporal, and macro analysis |
| Q3 · Feature engineering | 12 engineered features with domain rationale |
| Q4 · Regression modelling | OLS, Ridge, Lasso, ElasticNet with VIF & diagnostics |
| Q5 · Business recommendations | 5 board-ready actions with quantified impact |

## License

This project is licensed under the [MIT License](LICENSE).

---
*Made with Python & Jupyter · 2026*
