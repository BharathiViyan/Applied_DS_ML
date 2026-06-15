# Day 1 — Data Analysis

A single, runnable Jupyter notebook that walks through a complete data-analysis workflow — from raw NumPy arrays to a cleaned, encoded, split, and visualized dataset.

The clean, comment-free version intended for publishing is [`Day1_Data_Analysis_github.ipynb`](Day1_Data_Analysis_github.ipynb). The annotated teaching version (with explanations) is [`Day1_Data_Analysis.ipynb`](Day1_Data_Analysis.ipynb).

## Contents

The notebook is organized into five parts:

| Part | Topic | What it covers |
|------|-------|----------------|
| **Part 1** | NumPy | Array attributes, indexing, slicing, reshaping, concatenation/splitting, and descriptive statistics (mean, median, mode, variance, std, IQR, correlation, covariance, z-score, histogram) |
| **Part 2** | Pandas | `Series`, `DataFrame`, `Index`; selection with `.loc`/`.iloc`; filtering; operating on data with automatic index alignment |
| **Part 3** | Data Preprocessing (Part 1) | Data collection, cleaning (missing values, outliers, duplicates), transformation (`groupby`, `pivot_table`), and feature scaling/normalization/standardization |
| **Part 4** | Data Preprocessing (Part 2) | Feature selection, handling imbalanced data (up/down-sampling), categorical encoding, and train/validation/test splitting |
| **Part 5** | Data Visualization | Histogram, box plot, pie chart, scatter plot, violin plot, bar chart, pair plot, and strip plot |

## Dataset

The preprocessing and visualization sections use the **Titanic** dataset, expected at:

```
data/titanic.csv
```

## Requirements

- Python 3.9–3.12
- Packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1. Open the notebook in VS Code or Jupyter.
2. Select a Python kernel with the packages above installed.
3. Run the cells top to bottom (Part 1 → Part 5).

> Each part is self-contained for its imports, so you can also jump to a specific section after running its setup cell.

## Files

| File | Description |
|------|-------------|
| `Day1_Data_Analysis.ipynb` | Full notebook with explanations and comments |
| `Day1_Data_Analysis_github.ipynb` | Clean version — main headings only, no comments or outputs |
| `data/titanic.csv` | Dataset used in Parts 3–5 |
