# Capstone project - Hospital Readmission Prediction

Welcome to my capstone project "Predicting Hospital Readmission Within 30 Days Using Patient and Clinical Data".
Every day, thousands of patients are admitted to hospitals. However, in some cases, they are readmitted within a short period, even after receiving similar care. The goal of this project is to build a machine learning model that can predict 30-day readmissions based on factors such as age, gender, race, primary diagnosis, comorbidities, and discharge information. 

## Tools & Libraries
- Python, Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## Key Steps
1. Cleaned and preprocessed dataset (~70,000 patient records).  
2. Explored correlations between patient demographics, diagnoses, and readmissions.  
3. Built logistic regression, decision tree, and random forest models.  
4. Evaluated with ROC-AUC, accuracy, and recall metrics.  

## Results
- Best model: Random Forest (AUC: 0.81)  
- Top predictors: number of inpatient visits, discharge disposition, age group.  
