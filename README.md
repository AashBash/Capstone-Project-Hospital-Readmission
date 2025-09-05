# Capstone Project - Hospital Readmission
Welcome to my capstone project "Predicting Hospital Readmission Within 30 Days Using Patient and Clinical Data".
Every day, thousands of patients are admitted to hospitals. However, in some cases, they are readmitted within a short period, even after receiving similar care. The goal of this project is to build a machine learning model that can predict 30-day readmissions based on factors such as age, gender, race, primary diagnosis, comorbidities, and discharge information.

By identifying high-risk patients early, hospitals can implement targeted interventions and improve the quality of care.

## Technologies:
1. Jupyter Notebook
2. Python and its Libraries (Pandas, NumPy, Matplotlib, Seaborn)
3. Machine Learning algorithms (Logistic Regression, Random Forest, XGBoost)
4. Github

## Key Insights:
My project aimed to predict hospital readmissions using various machine learning models, including Logistic Regression, Random Forest and Gradient Boosting. Despite thorough preprocessing and model tuning, the predictive performance across these models had poor outcome.

AUC Scores: Ranged from approximately 0.47 to 0.53, indicating limited discriminative ability.

Accuracy: While some models achieved higher accuracy, this was misleading due to class imbalance, with models predominantly predicting the majority class.

Confusion Matrices: Revealed that models struggled to correctly identify readmitted patients, often misclassifying them as non-readmitted. The number of medications, patient age, and prior length of stay, indicating that patient history and treatment complexity play roles in readmission likelihood. Several factors contributed to the models' limited performance: Insufficient Feature Set: The dataset lacked comprehensive clinical details such as specific procedures, medication types, and vital signs, which are crucial for accurate predictions

Class Imbalance: A disproportionate number of non-readmitted patients led to models biased towards predicting the majority class.

Model Limitations: Standard machine learning models may not capture the complex patterns associated with hospital readmissions without richer data.

