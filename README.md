# Data-Analysis-for-Business

# Hitters Salary Prediction Project

This project was developed as part of the *Data Analysis for Business (DAB25)* course at LUISS Guido Carli. The aim is to analyze and model baseball player performance data from the Hitters dataset to predict salary levels using **multinomial logistic regression** and compare it with other machine learning models.

## Project Overview

We classify players into salary categories (`LowSalary`, `MediumSalary`, `HighSalary`) based on salary tertiles, then apply and evaluate several models to predict these categories using career and performance statistics.

## Key Objectives

- Preprocess the dataset (handle NAs, transform variables, scale features)
- Engineer the target variable (`SalaryLevel`) from continuous salary data
- Perform **Exploratory Data Analysis** with visualizations and statistical summaries
- Fit a **multinomial logistic regression model** with the full set of predictors
- Evaluate model performance using **cross-validation** (method selected via random seed)
- Optimize the model using **stepwise selection** and **Lasso regression**
- Compare with a **Random Forest** model
- Analyze accuracy, kappa statistics, and confusion matrices
- Visualize key results and interpret insights

## Files in this Repo

| File | Description |
|------|-------------|
| `ProjectWork_XX.Rmd` | Main R Markdown file containing code, analysis, and explanations |
| `ProjectWork_XX.html` | Rendered HTML output of the analysis |
| `Hitters.csv` | Dataset containing player statistics and salaries |
| `.gitignore` | Ignoring unnecessary system and RStudio files |
| `README.md` | This file – project overview and structure |

## Tools & Libraries

- **R** and **R Markdown**
- `nnet` (multinomial logistic regression)
- `caret` (cross-validation and performance evaluation)
- `glmnet` (Lasso)
- `randomForest` (Random Forest model)
- `ggplot2` (visualization)
- `dplyr`, `tidyr` (data manipulation)

## What We Learned

- How to convert continuous outcomes into meaningful categories
- Trade-offs between model complexity and interpretability
- The value of feature selection in predictive modeling
- Practical use of cross-validation to assess generalization
- Comparing performance across multiple model types

## Dataset Info

The dataset (`Hitters.csv`) includes 20+ variables describing major league baseball players’ performance during the 1986 season and their salaries in 1987.

---

> Developed for the LUISS DAB25 course. All code and analysis are for academic use only.
