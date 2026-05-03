# Loan Default Risk Predictor

A data science and machine learning project focused on predicting borrower loan default risk using financial and demographic indicators.

## Project Overview

This project analyzes 32,000+ real-world borrower records to identify the strongest factors associated with loan default, including income, debt burden, employment stability, home ownership, loan intent, and prior credit history.

Using data cleaning, exploratory analysis, and predictive modeling, this project evaluates both statistical relationships and machine learning performance in credit risk prediction.

## Key Results

- 87.7% Random Forest Accuracy
- Loan-to-income ratio was the strongest predictor of default
- Prior default history significantly increased future default risk
- Higher income and longer employment history were associated with lower default probability

## Methods Used

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Logistic Regression
- Random Forest Classification

## Tech Stack

- Python
- pandas
- NumPy
- scikit-learn
- statsmodels
- matplotlib
- seaborn
- Jupyter Notebook

## Business Relevance

This project demonstrates practical applications of machine learning in:

- Credit risk assessment
- Financial behavior analysis
- Borrower segmentation
- Predictive decision support
## Key Takeaway

Financial strain indicators, particularly debt burden and prior default history, were the strongest predictors of loan default risk. The analysis consistently showed that borrower financial stability plays a major role in repayment outcomes, reinforcing the value of data-driven credit risk assessment.

## Repository Structure

```bash
loan-default-risk-predictor/
│── 00-ProjectProposal.ipynb
│── 01-DataCheckpoint.ipynb
│── 02-EDACheckpoint.ipynb
│── 03-FinalProject.ipynb
│── modules/
│── data/
│── results/
└── README.md
