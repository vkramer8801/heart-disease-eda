# Heart Disease Exploratory Data Analysis

## Overview
This project explores clinical risk factors associated with heart disease using exploratory data analysis (EDA). The goal is to identify patterns and relationships between patient characteristics and heart disease outcomes.

## Dataset
- Source: Kaggle Heart Disease Dataset
- Observations: ~900 patients
- Target Variable: HeartDisease (0 = No, 1 = Yes)

## Key Questions
- Which variables are most associated with heart disease?
- How do exercise-related features impact risk?
- What clinical indicators show the strongest relationships?

## Key Insights
- ST Slope is a strong predictor, with flat/down slopes linked to higher risk
- Oldpeak shows the strongest positive correlation with heart disease
- Max heart rate is negatively correlated with heart disease
- Exercise-induced angina is associated with higher likelihood of disease

## Methods Used
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis

## Tools & Technologies
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Project Structure
- `heart_disease_eda.ipynb` → full analysis
- `heart.csv` → dataset
- `/images` → saved visualizations
