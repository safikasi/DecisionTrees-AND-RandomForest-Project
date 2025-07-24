# 🌳📈 Loan Repayment Prediction Project
![Python](https://img.shields.io/badge/Python-%E2%9D%A4%EF%B8%8F%203.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-%F0%9F%94%8E%201.2%2B-orange)
![Machine-Learning](https://img.shields.io/badge/Machine--Learning)

# Project Overview
Predicting Lending Club loan repayments using Decision Trees and Random Forest classifiers on 2007-2010 data.

# 🔍 Key Insights

## FICO Score Analysis

<img width="582" height="381" alt="1" src="https://github.com/user-attachments/assets/52891cef-e62d-4851-8ac2-129a0faa76c6" />

<img width="577" height="378" alt="2" src="https://github.com/user-attachments/assets/f85d0ef7-48fc-480a-acd0-97da6aa39a4d" />

Credit policy=1 borrowers have higher FICO scores

Most scores cluster between 650-750

Strong negative correlation with interest rates (pearson=0.71)

## Loan Characteristics

<img width="637" height="433" alt="3" src="https://github.com/user-attachments/assets/070b9a4b-cc2c-4dcb-be4c-74523b4c598a" />

<img width="721" height="377" alt="5" src="https://github.com/user-attachments/assets/5d679a82-baf3-4b88-b852-e7ed9d782987" />

Top loan purpose: Debt consolidation (48.7%)

Lower FICO → Higher default rates

Credit policy=1 group repays better

# � Model Performance

## Decision Tree

              precision    recall  f1-score   support
           0       0.85      0.82      0.84      2431
           1       0.19      0.23      0.20       443
    accuracy                           0.73      2874

## Random Forest (Improved)

              precision    recall  f1-score   support
           0       0.85      1.00      0.92      2431
           1       0.57      0.03      0.05       443
    accuracy                           0.85      2874

## 🛠️ Installation

git clone https://github.com/safikasi/DecisionTrees-AND-RandomForest-Project.git
pip install -r requirements.txt

# About Me

✨ **Safwan Khan Kasi**  
*DS/ML Enthusiast | [GitHub](https://github.com/safikasi) | [LinkedIn](https://www.linkedin.com/in/safwan-kasi-2b5358292/)*
