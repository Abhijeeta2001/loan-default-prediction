# Loan Default Prediction Pipeline

An end-to-end machine learning system designed to assess credit risk and predict the likelihood of loan default using supervised learning algorithms.

[![Python package](https://github.com/Abhijeeta2001/loan-default-prediction/actions/workflows/python-package.yml/badge.svg)](https://github.com/Abhijeeta2001/loan-default-prediction/actions/workflows/python-package.yml)

---

## 📌 Project Overview

Accurately predicting loan defaults enables financial institutions to mitigate credit losses and optimize risk-adjusted lending decisions. This project implements a modular ML pipeline covering data preprocessing, model training, performance evaluation, and risk reporting.

### Key Highlights
* **Modular Pipeline**: Clean separation of data processing, training, and evaluation scripts.
* **Model Benchmarking**: Implementation and comparison of predictive algorithms for financial risk assessment.
* **Evaluation Metrics**: Tuned for imbalanced credit datasets focusing on ROC-AUC, PR-AUC, Precision, and Recall.
* **Comprehensive Project Report**: Includes detailed analysis and methodology documentation in PDF format.

---

## 📁 Repository Structure

```text
├── Loan_Default_Submission/
│   ├── code/
│   │   ├── preprocessing.py   # Feature cleaning, encoding, and imputation
│   │   ├── models.py          # Model architecture and training configurations
│   │   ├── evaluation.py      # Performance metrics and validation logic
│   │   └── main.py            # Main pipeline execution entry point
│   ├── notes/
│   │   └── NOTES.txt          # Implementation notes and observations
│   └── report/
│       └── Loan_Default_Prediction_Project_Abhijeeta_Panigrahi.pdf
├── tests/
│   └── test_basic.py          # CI verification tests
├── .github/workflows/         # Automated Python package CI
└── requirements.txt
