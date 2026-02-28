# Streaming & E-commerce Analysis — Netflix & Amazon

This repository contains interactive Jupyter notebooks that perform exploratory data analysis and visualizations for Netflix content and Amazon shopping datasets.

**Contents**

- `netflix_analysis.ipynb` — Exploratory analysis, visualizations, and insights from the Netflix dataset.
- `amazon_analysis.ipynb` — Exploratory analysis, visualizations, and insights from the Amazon shopping dataset.

**Project Summary**

This project provides cleaned, reproducible analyses for streaming-platform and e-commerce data. The notebooks include data cleaning steps, exploratory data analysis (EDA), visualizations (distributions, trends, genre/category analysis), and simple modeling examples where appropriate. The aim is to make it easy to reproduce the analyses and adapt the notebooks for further research or reporting.

**Getting Started**

1. Install dependencies (recommended in a virtual environment):

```
python -m venv .venv
.venv\Scripts\activate    # Windows
pip install jupyter pandas numpy matplotlib seaborn scikit-learn plotly
```

2. Launch Jupyter and open the notebooks:

```
jupyter notebook
```

3. Update dataset paths inside the notebooks if your CSVs are located in a `data/` folder or elsewhere.

**Notes on Data**

- The notebooks expect local datasets (CSV or similar). If you used Kaggle or other public sources, keep the original source references in the notebooks or a `data/README.md`.
- Do not include any private or copyrighted datasets in the repository.

**Results & Visuals**

Each notebook contains charts and tables that highlight key insights such as content or category distribution, release-year or time trends, rating or review distributions, and other platform- or marketplace-specific patterns.

