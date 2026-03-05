# Customer Churn Prediction – BCG Strategy Consulting Simulation

## Project Overview

This project was completed during the AXAIA Data Science Virtual Internship.

Our team analyzed customer churn in the energy sector using historical customer data and pricing information. The objective was to identify key drivers of churn and build a predictive model that could help the business retain customers.

Our team of eight analysts delivered the final presentation and received the Best Presentation Award.

---

## Business Problem

Customer churn significantly impacts revenue in subscription-based industries.

The consulting hypothesis was that price sensitivity might be the primary driver of customer churn.

This project investigates whether price changes truly influence churn or if other behavioral factors are more important.

---

## Dataset

The analysis used three datasets:

- Historical customer data
- Historical pricing data
- Churn indicator dataset

---

## Project Workflow

1. Business Understanding
2. Exploratory Data Analysis
3. Feature Engineering
4. Predictive Modeling
5. Insight Generation

---

## Feature Engineering

Several new variables were created to capture price volatility and behavioral patterns:

- Average price change across months
- Maximum price variance
- Log transformation of skewed variables
- Customer duration features
- Dummy variables for categorical data

---

## Modeling

The problem was framed as a binary classification task.

Models used:

- Logistic Regression
- Random Forest

Evaluation metrics included:

- Accuracy
- Precision
- Recall

Recall was particularly important due to the class imbalance in churn.

---

## Key Insight

Contrary to expectations, price sensitivity was not the strongest predictor of churn.

Behavioral variables such as customer tenure and usage patterns had stronger predictive power.

---

## Business Recommendations

- Implement early churn detection systems
- Develop targeted retention campaigns
- Improve customer engagement strategies

---

## Tools Used

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib / Seaborn

---

## Author

Taofeeqah Balogun
