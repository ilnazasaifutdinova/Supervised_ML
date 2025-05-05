# Supervised Machine Learning – Loan Approval Prediction - ML Model training and building

This project focuses on using machine learning techniques to analyze customer financial details and predict whether a loan application is likely to be approved or rejected. 
A link for the [Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset) from Kaggle.

## 📌 Project Goal

Build classification models to predict loan approval outcomes using supervised machine learning. The project includes data preprocessing, model training, evaluation, and model selection.

## 🧠 Techniques Used

- **Logistic Regression**
- **Decision Tree Classifier**
- Hyperparameter tuning using `GridSearchCV`
- Cross-validation
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC AUC
- Data visualization (EDA & Feature Importance)

## 📊 Dataset

The dataset includes details such as:
- Applicant income
- Loan amount
- Loan term
- CIBIL score
- Asset values
- Education level
- Employment status
- Target variable: `loan_status` (Approved / Rejected)

## ✅ Tasks Completed

1. **Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Modeling**  
   - Trained Logistic Regression and Decision Tree models  
   - Performed cross-validation and hyperparameter tuning  

3. **Evaluation**  
   - Compared models using key metrics and visualizations  
   - Analyzed feature importance  

4. **Conclusion**  
   - Decision Tree selected as the final model based on performance

## 📈 Key Visualizations

- Loan status distribution
- Boxplot: Annual income vs Loan status
- Correlation heatmap
- Feature importance (Decision Tree)

## 🧾 Final Report

See the full report in the [`loan_approval_prediction.ipynb`](./loan_approval_prediction.ipynb) notebook or exported PDF.

## 📂 Structure 
Supervised_ML/

* Dataset

   * loan_approval_dataset.csv

* Loan_approval_prediction

   * loan_approval_prediction.ipynb

* Report.pdf

* README.md
