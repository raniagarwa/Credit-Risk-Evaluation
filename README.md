# Credit Risk Evaluation 
## Overview
This project focuses on evaluating credit risk using Machine Learning and Support Vector Machine (SVM). The objective is to classify loan applicants into **good credit (low risk)** and **bad credit (high risk)** categories to help financial institutions reduce the probability of loan defaults.

## Problem Statement
Credit risk is the possibility that a borrower may fail to repay a loan obligation. Manual credit assessment can be time-consuming and biased. This project automates credit risk classification using an SVM-based predictive model.

## Dataset
- Dataset: German Credit Data
- Source: Kaggle
- Records: 1000 instances
- Features Used:
  - Age
  - Sex
  - Job
  - Housing
  - Saving Accounts
  - Checking Account
  - Credit Amount
  - Duration
  - Purpose

## Methodology
1. Data Preprocessing
   - Categorical encoding using Label Encoding
   - Feature scaling using StandardScaler

2. Train-Test Split
   - Training Data: 80%
   - Testing Data: 20%

3. Model Development
   - Support Vector Machine (SVM) Classifier
   - Kernel-based classification approach

4. Model Evaluation
   - Confusion Matrix
   - Accuracy Score
   - Precision
   - Recall
   - F1-Score

## Mathematical Foundation
The project is based on Support Vector Machine concepts:
- Maximum Margin Classifier
- Hyperplane Optimization
- Soft Margin SVM
- Kernel Methods (Polynomial / Nonlinear Classification)

## Results
- Model Accuracy: 97.5%
- Correct Predictions: 195 out of 200 test samples

The model demonstrated strong performance in classifying prospective customers into credit risk categories.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Project Structure
```bash
Credit-Risk-Evaluation-SVM/
│
├── data/
│   └── german_credit_data.csv
│
├── notebooks/
│   └── credit_risk_evaluation.ipynb
│
├── src/
│   └── svm_model.py
│
├── results/
│   └── confusion_matrix.png
│
├── report.pdf
├── requirements.txt
└── README.md
```

## Installation
Clone the repository:

```bash
git clone https://github.com/YourUsername/Credit-Risk-Evaluation-SVM.git
cd Credit-Risk-Evaluation-SVM
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python svm_model.py
```

## Applications
- Credit Approval Systems
- Loan Default Prediction
- Banking Risk Assessment
- Financial Decision Support Systems

## Future Improvements
- Hyperparameter tuning using GridSearchCV
- Compare SVM with Random Forest and Logistic Regression
- Deploy as a web application
- Use real-world large-scale credit datasets

## Author
Rani  
M.Tech, Computer Science & Data Processing  
Indian Institute of Technology Kharagpur

## References
- Bishop, Pattern Recognition and Machine Learning
- Deisenroth, Mathematics for Machine Learning
- Credit Risk Analysis using Support Vector Machines# Credit-Risk-Evaluation
