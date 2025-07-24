# 🌳📈 Loan Repayment Prediction Project

![Machine Learning in Finance](https://miro.medium.com/max/1400/1*ZIKAqZvFoTm2-4m9XslQNw.jpeg)

# Project Overview
Predicting Lending Club loan repayments using Decision Trees and Random Forest classifiers on 2007-2010 data.

# 🔍 Key Insights

## FICO Score Analysis

(1.png)

(2.png)

Credit policy=1 borrowers have higher FICO scores

Most scores cluster between 650-750

Strong negative correlation with interest rates (pearson=0.71)

## Loan Characteristics

(3.png)

(5.png)

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