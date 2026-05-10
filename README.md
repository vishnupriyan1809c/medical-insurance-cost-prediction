# Medical Insurance Cost Prediction

Predicting annual medical insurance charges using **Multiple Linear Regression** and **Polynomial Regression** on 1,338 individual records.

---

## Project Overview

Healthcare costs are one of the most significant financial burdens faced by individuals worldwide. This project explores which personal and lifestyle factors drive insurance premiums — and builds regression models to predict them accurately.

**Dataset:** Medical Cost Personal Dataset — 1,338 records, 7 features

---

## What I Did

- Performed Exploratory Data Analysis (EDA) to uncover patterns in the data
- Preprocessed data — encoded categorical variables, feature scaling
- Built and compared Multiple Linear Regression vs Polynomial Regression
- Evaluated models using R² Score, RMSE, and 10-Fold Cross Validation

---

## Model Results

| Model | Testing Accuracy | Testing RMSE | 10-Fold CV Score |
|---|---|---|---|
| Multiple Linear Regression | 78.1% | $5,829 | 0.7307 |
| Polynomial Regression | 86.4% | $4,595 | 0.8256 |

Polynomial Regression won — 8% higher accuracy and $1,234 less prediction error per person.

---

## Key Findings

| Factor | Impact |
|---|---|
| Smoking | Smokers pay 3-4x more — strongest predictor by far |
| Age | Charges steadily increase with age |
| BMI + Smoking | Combined effect drives charges to $40,000-$60,000 |
| Children / Sex | Very weak predictors |

> Key Takeaway: Stopping smoking is the single most impactful lifestyle change to reduce insurance costs.

---

## Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / VS Code

---

## Files

| File | Description |
|---|---|
| `Medical_Insurance_Cost_Prediction.ipynb` | Full project notebook |
| `insurance.csv` | Dataset |

---

## Author

**Vishnupriyan** — Data Science Student  
[GitHub](https://github.com/vishnupriyan1809c)
