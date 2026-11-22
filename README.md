# Feature Engineering & Preprocessing Pipeline

## Project Overview
A reusable and leak-free Machine Learning preprocessing pipeline built using Python and Scikit-Learn.

This project demonstrates how to prepare complex tabular data for machine learning through feature encoding, scaling, missing value imputation, correlation analysis, and feature importance evaluation.

## Dataset
- Dataset: Adult Census Income Dataset
- Source: OpenML
- Task: Binary Classification
- Target: Income Class

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Implementation
1. Dataset loading and exploration
2. Missing value identification and handling
3. Train-test splitting before preprocessing
4. Numerical preprocessing using SimpleImputer and StandardScaler
5. Categorical preprocessing using SimpleImputer and OneHotEncoder
6. ColumnTransformer implementation
7. Correlation matrix and heatmap analysis
8. Mutual Information feature importance
9. Random Forest classification
10. Model evaluation and pipeline serialization

## Data Leakage Prevention
The dataset is split into training and testing sets before fitting preprocessing transformations.

The preprocessing pipeline is fitted only on training data and subsequently applied to test data using transform().

## Model Evaluation
The Random Forest classifier is evaluated using:
- Accuracy
- Classification Report
- Confusion Matrix

## Project Structure
```text
Feature-Engineering-Preprocessing-Pipeline/
│
├── feature_engineering_pipeline.ipynb
├── feature_engineering_pipeline.pkl
└── README.md
```

## How to Run

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter joblib
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `feature_engineering_pipeline.ipynb` and run all cells.

## Learning Outcomes
- Building reusable Scikit-Learn pipelines
- Handling numerical and categorical features
- Preventing data leakage
- Performing correlation and feature importance analysis
- Evaluating classification models

## Author
Parul Pal
