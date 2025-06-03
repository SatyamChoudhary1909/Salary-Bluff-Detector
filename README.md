# Salary-Bluff-Detector

This project aims to **detect possible bluffing in salary reports** using **Polynomial Regression**. By analyzing a dataset of position levels and corresponding salaries, we predict realistic salary ranges and flag outliers or unrealistic claims — aka "bluffs."

---

## Project Overview

In many companies, candidates may exaggerate their salary expectations. This model uses **Linear** and **Polynomial Regression** (Degrees 2, 3, and 4) to analyze the salary trends across different job levels and **detect anomalies** in predictions — which could indicate bluffing.

---

## Machine Learning Techniques Used

- **Linear Regression**
- **Polynomial Regression (Degrees 2, 3, 4)**
- **Evaluation Metrics**:
  - Root Mean Square Error (RMSE)
  - R² Score (Coefficient of Determination)

---

## Dataset

- **Name**: Position_Salaries.csv
- **Source**: Included in the project (used from Kaggle)
- **Columns**:
  - `Position`: Job title (not used directly in the model)
  - `Level`: Numeric level of the position (independent variable)
  - `Salary`: Actual salary (dependent variable)

---

## Visualization

Each model's predictions are plotted against the actual data to observe how well they fit. The higher-degree polynomial models show better fitting and can help detect anomalies in salary predictions.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bluff-detection-salary-prediction.git
