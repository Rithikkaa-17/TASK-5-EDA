# TASK-4-EDA
#  Superstore Sales Data Analysis

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Superstore dataset using Python. The dataset consists of retail transactional data including sales, profits, customer demographics, shipment details and regional performance across various product categories.

# Files Included

| File Name                                | Description                                           |
| ---------------------------------------- | ----------------------------------------------------- |
| Sample - Superstore.csv                  | Source dataset used for analysis                      |
| task_5_eda.py/TASK-5-EDA.ipynb           | Python script containing the full EDA pipeline        |
| TASK-5-EDA.ipynb - RITHIKKAA.pdf         | Notebook version of the analysis (PDF export)         |
| Superstore Dataset Analysis Report.pdf   | Detailed written report with insights and conclusions |


# Project Objective

* To understand the sales performance across categories and regions
* To identify factors impacting profit and loss
* To detect patterns in customer segments, shipping modes and discounts
* To visualize relationships among key metrics using plots and statistics

# Key Insights

* Technology category drives the most profit, while Furniture has high sales but low profitability.
* Discounts show a negative correlation with Profit (r ≈ -0.22).
* Consumer segment dominates in sales volume but is less profitable than Corporate in some areas.
* No missing or duplicate data, making it suitable for advanced ML modeling.

# Analysis Performed

1. Data Cleaning & Overview

   * `df.info()`, `df.describe()`, missing/duplicate checks

2. Univariate Analysis

   * Histograms for `Sales`, `Profit`, `Quantity` and `Discount`

3. Bivariate Analysis

   * Correlation heatmaps
   * Scatterplots (e.g., `Sales` vs `Profit`, `Discount` vs `Profit`)
   * Boxplots by `Segment` and `Region`

4. Category-Level Insights

   * Bar charts for total sales/profit by `Category` and `Sub-Category`

5. Advanced Visuals

   * Pairplot, regression plots, segment-wise breakdown

# Tools & Libraries Used

* Python 3
* Pandas
* Seaborn
* Matplotlib
* Google Colab / Jupyter Notebook

# How to Run

1. Install required packages:

```bash
pip install pandas seaborn matplotlib
```

2. Run `task_5_eda.py` or open the notebook in Jupyter/Colab.

3. Ensure `Sample - Superstore.csv` is in the same directory.

# Recommendations (from analysis)

| Area        | Recommendation                                                       |
| ----------- | -------------------------------------------------------------------- |
| Discounts   | Cap discounts to avoid losses                                        |
| Product Mix | Promote high-margin items, reduce dependency on low-profit furniture |
| Segments    | Adjust targeting strategies for Corporate/Home Office                |
| Logistics   | Review regional logistics efficiency                                 |
| Analytics   | Leverage clean data for ML modeling & forecasts                      |

# Author

Rithikkaa
Task 5 - EDA Submission

