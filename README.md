# Heart Disease Exploratory Data Analysis

## Overview
This project explores clinical risk factors associated with heart disease using exploratory data analysis (EDA). The goal is to identify meaningful patterns between patient characteristics and heart disease outcomes, and highlight which variables may be most relevant for risk assessment.

Understanding these relationships can help support early detection and inform clinical decision-making.

---

## Dataset
- Source: Kaggle Heart Disease Dataset  
- Observations: ~900 patients  
- Target Variable: HeartDisease (0 = No, 1 = Yes)  

### Features include:
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Max Heart Rate  
- Oldpeak (ST depression)  
- ST Slope  
- Exercise-Induced Angina  

---

## Key Questions
- Which variables are most strongly associated with heart disease?  
- How do exercise-related metrics impact outcomes?  
- What clinical indicators show the strongest relationships?  
- Are there clear patterns that separate high-risk vs low-risk patients?  

---

## Key Insights
- ST Slope is one of the strongest predictors of heart disease, with flat and downward slopes associated with higher risk  
- Oldpeak shows the strongest positive correlation with heart disease  
- Max heart rate is negatively correlated with heart disease outcomes  
- Exercise-induced angina is associated with increased likelihood of heart disease  
- Age shows a moderate positive relationship with heart disease risk  

---

## Visualizations

### Correlation Matrix
![Correlation Matrix](Images/correlation_matrix.png)  
*Figure 1: Correlation matrix showing relationships between numerical variables and heart disease.*

---

### ST Slope vs Heart Disease
![ST Slope](Images/st_slope_vs_heart_disease.png)  
*Figure 2: Patients with flat or downward ST slopes show higher rates of heart disease.*

---

### Oldpeak vs Heart Disease
![Oldpeak](Images/oldpeak_vs_heart_disease.png)  
*Figure 3: Higher ST depression (oldpeak) is associated with increased heart disease risk.*

---

### Max Heart Rate vs Heart Disease
![MaxHR](Images/maxhr_vs_heart_disease.png)  
*Figure 4: Lower maximum heart rate is associated with higher likelihood of heart disease.*

---

## Methods Used
- Exploratory Data Analysis (EDA)  
- Data Visualization  
- Correlation Analysis  
- Categorical Feature Analysis  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

---

## Project Structure
- `Data/` → dataset  
- `Images/` → saved visualizations  
- `Notebooks/` → full analysis notebook  
- `README.md` → project overview  

---

## How to Run
1. Clone the repository  
2. Open `Notebooks/heart_disease_eda.ipynb`  
3. Run all cells  

---

## Data Source
- Fedesoriano. (2021). *Heart Failure Prediction Dataset*.  
  Available at: https://www.kaggle.com/fedesoriano/heart-failure-prediction  

---

## Future Improvements
- Apply machine learning models for prediction  
- Perform feature importance analysis  
- Explore class imbalance handling techniques  
- Test model performance across different algorithms  

---

## Author
Vanessa Kramer
