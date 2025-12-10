# Diwali Sales Analysis

A small exploratory data analysis (EDA) and visualization project analyzing Diwali sales data.

## Project overview

This repository contains a dataset and a Jupyter Notebook that analyzes Diwali sales data. The analysis focuses on cleaning the dataset, exploring sales patterns across cities/locations, identifying top-selling products, and visualizing trends useful for business insights.

## Files

- `Diwali Sales Data.csv` — Raw dataset used for the analysis.
- `Diwali_Sales_Analysis.ipynb` — Jupyter Notebook with EDA, cleaning steps, visualizations, and conclusions.

## Quick start

1. Install Python 3.8+.
2. (Recommended) Create and activate a virtual environment:

   - Windows (PowerShell):
     ```powershell
     python -m venv .venv; .\.venv\Scripts\Activate.ps1
     ```

3. Install common data-analysis packages (example):

   ```powershell
   pip install pandas numpy matplotlib seaborn jupyterlab plotly openpyxl
   ```

4. Open the notebook:

   - Using Jupyter Notebook/Lab:
     ```powershell
     jupyter notebook "Diwali_Sales_Analysis.ipynb"
     # or
     jupyter lab
     ```

   - Or open directly in VS Code (recommended if you already use it).

## Suggested requirements

If you want a reproducible environment, create a `requirements.txt` with at least:

pandas
numpy
matplotlib
seaborn
plotly
openpyxl
jupyterlab

(You can generate this after installing packages using `pip freeze > requirements.txt`.)

## What the notebook does

- Loads and inspects `Diwali Sales Data.csv`.
- Cleans columns and missing/incorrect values.
- Performs aggregation to find top-selling items, highest revenue locations, and seasonal trends.
- Visualizes results using charts (bar charts, line charts, heatmaps, etc.).
- Summarizes key business insights and recommendations for sales/marketing.

## Notes and assumptions

- The analysis is exploratory and intended for demonstration/learning. Any production use should include additional validation and tests.
- If the dataset contains non-UTF8 encodings, open it in an editor or pass the correct `encoding` argument to `pandas.read_csv()`.

## Next steps (suggested)

- Add a `requirements.txt` for reproducibility.
- Add a short `SUMMARY.md` of key findings extracted from the notebook.
- Optionally add a small test script that verifies the dataset loads and basic expected columns exist.
- Add a GitHub Actions workflow to run a notebook linting/validation step on push.

## Author

Repository maintained by the project owner.

---

If you'd like, I can also generate a `requirements.txt`, add a short summary file of key insights from the notebook, or convert the notebook outputs to an HTML report. Which would you prefer next?