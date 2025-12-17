# COVID-19 Predictive Modeling

## Project Overview
This project applies machine learning techniques to predict COVID-19 trends using historical pandemic data.
It builds upon cleaned and preprocessed datasets and focuses on supervised regression and classification, model evaluation, and interpretation.

The objective is to demonstrate practical predictive modeling skills on a real-world, time-dependent dataset.

---

## Dataset
- **Source:** Public COVID-19 datasets
- **Files:** `raw_covid_data.csv`,
- **Description:** Raw and preprocessed datasets used for feature engineering, modeling, and evaluation

---

## Project Structure

covid-19-predictive-modeling/
```
│
├── datasets/
│   ├── covid_19_clean_complete.csv

│
├── notebooks/
│   ├── COVID19_Analysis_and_predictive_modeling.ipynb

│
├── README.md
└── .gitignore
```

---

## Modeling Workflow

### Data Preprocessing
- Cleaned and formatted raw COVID-19 data
- Converted dates to datetime format and sorted chronologically
- Handled missing values and inconsistencies

### Feature Engineering
- Created time-based and lag features to capture trends
- Prepared features for model training

### Model Training
- Applied linear regression for prediction
- Used chronological train-test split to prevent data leakage

### Model Evaluation
- Assessed model performance using R² and Mean Absolute Error (MAE)
- Visualized predictions against actual trends
- Interpreted model outputs in the context of real-world patterns

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Learnings
- Importance of lag features in time-dependent predictions
- Chronological train-test split prevents data leakage
- Regression models can capture overall trends in pandemic data

---

## Potential Improvements
- Include additional regression metrics such as RMSE
- Explore advanced models in the future
- Enhance interpretation with more visual comparisons

---

## Author
Saba Arif
