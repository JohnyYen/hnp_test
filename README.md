# Hipótesis No Paramétrica - Elective Course Repository

Repository for statistical tests and implementations for the non-parametric hypothesis testing elective course.

## Context

This repository contains implementations and notebooks for various statistical tests developed as part of the "Hipótesis No Paramétrica" elective course.

## Project Structure

```
.
├── data/                    # CSV datasets
├── notebook/                # Jupyter notebooks
│   └── kruskal_wallis.ipynb
├── kruskal_wallis.py        # Test implementations
├── wilconxon.py            # Test implementations
└── README.md
```

## Prerequisites

- Python 3.x
- Required libraries:
  - pandas
  - scipy
  - seaborn
  - matplotlib

### Installation

Install the required dependencies:

```bash
pip install pandas scipy seaborn matplotlib
```

Alternatively, if you have Jupyter installed:

```bash
pip install pandas scipy seaborn matplotlib jupyter
```

## How to Run

### A. Running Python Scripts

Execute any Python script from the root directory:

```bash
python [script_name].py
```

Example:
```bash
python kruskal_wallis.py
```

### B. Running Jupyter Notebooks

**Option 1: Launch Jupyter and navigate manually**

```bash
jupyter notebook
```

Then navigate to the `notebook/` folder and open the desired notebook (e.g., `kruskal_wallis.ipynb`).

**Option 2: Launch Jupyter in the notebook directory**

```bash
jupyter notebook notebook/
```

This will open Jupyter directly in the notebook directory.

### Running the Notebook

1. Open the notebook in Jupyter
2. Run cells individually by pressing `Shift + Enter` or use the "Run" button in the toolbar
3. Run all cells sequentially using `Cell > Run All` from the menu

## Data

Datasets are stored in CSV format in the `data/` folder. Scripts and notebooks reference these files for analysis.
