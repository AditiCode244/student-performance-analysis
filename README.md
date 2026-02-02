# Student Performance Analysis & Prediction

##  Project Overview
This project analyzes student academic performance using data science and machine learning techniques.
The goal is to help teachers understand which features influence student success and build a predictive model for early intervention.

## Problem Statement
Educational institutions often struggle to identify students at risk of poor academic performance. By analyzing past student data, we can discover patterns and predict final outcomes, helping teachers take preventive action.

##  Dataset Information
- Dataset: Student Performance Dataset
- Source: https://www.kaggle.com/datasets/devansodariya/student-performance-data
- Number of Students: 395 
- Features Include:
  - Study Time
  - Absences
  - Previous Grades (G1, G2)
  - Family Background
  - Internet Access
  - Extra Activities

##  Tools & Technologies
- Python – programming language
- Jupyter Notebook – interactive coding and visualization
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

##  Exploratory Data Analysis (EDA)
  Key Insights:
  
- Study time is positively correlated with final grades.
- Higher absences often lead to lower performance.
- Previous grades (G1, G2) are strong indicators of final grades.
- Visualizations (heatmaps, bar charts) help identify influential features.

##  Machine Learning Models Used
The following models were trained and evaluated:
- Linear Regression

Evaluation Metrics:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

##  Model Performance 
| Metric | Value |
|--------|-------|
| MAE    |  1.3394|
| MSE    | 4.4665 |
| R² Score | 0.7821|

##  How to Run This Project

1. Clone this repository  
2. Install required libraries  

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook  
4. Run all cells to see analysis and predictions


## Project Outcome
- Performed data cleaning and visualization
- Built a machine learning model to predict final grades
- Generated insights to help improve student performance

##  Future Improvements
- Add more machine learning models
- Hyperparameter tuning
- Build a web app using Streamlit
- Deploy the model online
  
##  Academic Purpose
This project is created as part of a college Data Science & Machine Learning assignment.

##  Author

**Aditi**  
BTech AI/ML Student | Aspiring Data Scientist
