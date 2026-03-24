# Blood-Donation-Prediction-using-Machine-Learning
Machine Learning project to predict blood donation behavior using Logistic Regression, TPOT, and Linear Regression with AUC evaluation, ROC analysis, and donor behavior insights.


##  Project Overview
This project aims to predict whether a blood donor will donate blood in a future campaign using historical donor data. The dataset includes behavioral features such as Recency, Frequency, Monetary value, and Time.

The project applies machine learning techniques along with data analysis to build predictive models and extract meaningful insights for blood donation forecasting.

---

##  Objectives
- Predict whether a donor will donate blood (Binary Classification)
- Compare multiple machine learning models
- Evaluate performance using AUC, ROC Curve, and Confusion Matrix
- Analyze donor behavior patterns
- Provide insights for improving blood donation campaigns

---

##  Dataset Description
The dataset contains 748 donor records with the following features:

- **Recency (months):** Months since last donation  
- **Frequency (times):** Total number of donations  
- **Monetary (c.c. blood):** Total blood donated  
- **Time (months):** Months since first donation  
- **Target:** Whether donor donated in March 2007 (1 = Yes, 0 = No)

---

##  Technologies Used
- Python 3.10
- Pandas, NumPy
- Scikit-learn
- TPOT (AutoML)
- Matplotlib, Seaborn

---

##  Project Workflow
1. Data Loading and Inspection  
2. Data Cleaning and Preprocessing  
3. Train-Test Split (Stratified)  
4. Feature Engineering (Log Normalization)  
5. Model Building  
6. Model Evaluation  
7. Model Comparison  
8. Behavioral Data Analysis  

---

##  Models Used

| Model | AUC Score |
|------|----------|
| Logistic Regression | **0.7891** |
| TPOT | 0.7637 |
| Linear Regression | 0.7622 |

---

##  Model Evaluation

### Confusion Matrix
Used to evaluate classification performance:
- True Positives
- True Negatives
- False Positives
- False Negatives

### ROC Curve
- Visual comparison of model performance
- Logistic Regression showed
