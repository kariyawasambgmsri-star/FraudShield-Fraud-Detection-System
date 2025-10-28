# FraudShield-Fraud-Detection-System
A Streamlit-based ML project for detecting fraudulent credit card transactions
FraudShield: Credit Card Fraud Detection System

 Project Overview

FraudShield is a machine learning–based system designed to detect fraudulent credit card transactions in real time.
It analyzes transaction patterns, balances, and transaction types to predict the likelihood of fraud.
The project uses *Python, Scikit-learn, Pandas, Matplotlib, and Streamlit* for model development and deployment.

 Objectives

* Identify patterns in financial transaction data.
* Train and evaluate machine learning models for fraud detection.
* Build a user-friendly web app using *Streamlit* for real-time predictions.
* Improve transaction security through data-driven insights.

System Architecture

Modules of the Project:

1. Data Preprocessing & EDA – Data cleaning, visualization, and class imbalance handling.
2. Model Development – Training and evaluating ML models (Logistic Regression, Random Forest).
3. Web App (Streamlit) – User interface for entering transaction data and viewing predictions.
4. Documentation & Deploymen – README, project report, and app deployment.

Technologies Used

| Category             | Tools & Libraries                                        |
| -------------------- | -------------------------------------------------------- |
| Programming Language | Python                                                   |
| Framework            | Streamlit                                                |
| Libraries            | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib |
| IDE                  | VS Code / Jupyter Notebook                               |
| Version Control      | Git & GitHub                                             |

Dataset

Source: Synthetic transaction dataset for fraud detection (6 million+ rows).
Key Columns: type, amount, oldbalanceOrg, newbalanceOrig, oldbalanceDest, newbalanceDest, isFraud
Fraud Rate: ~0.13%

How to Run the Project

1. Clone the repository

   bash
   git clone https://github.com/your-username/FraudShield-Fraud-Detection-System.git
   cd FraudShield-Fraud-Detection-System
   

2.*Install dependencies

   bash
   pip install -r requirements.txt
   

3. Run the Streamlit app

   bash
   streamlit run app/fraud_detection_app.py
   

4. View the app
   Open your browser and go to 👉 http://localhost:8501
Results

* Model Accuracy: *94%*
* Precision: *89%*
* Recall: *92%*
* Fraud transactions mostly found in: *CASH_OUT* and *TRANSFER* types

Team Members

| Name       | Student ID | Course                     | Role                       |
| ---------- | ---------- | -------------------------- | -------------------------- |
| [Member 1] | [ID]       | BSc (Hons) in Data Science | Data Preprocessing         |
| [Member 2] | [ID]       | BSc (Hons) in Data Science | Model Building             |
| [Member 3] | [ID]       | BSc (Hons) in Data Science | App Development            |
| [Member 4] | [ID]       | BSc (Hons) in Data Science | Documentation & Deployment |

 Future Improvements

* Add deep learning models for higher accuracy
* Implement real-time fraud detection with APIs
* Deploy app on the cloud (Streamlit Cloud / AWS / Heroku)
* Improve dataset quality with real transaction samples

Academic Details
Module: DS205.3 – Data Science in Python
Semester: [Enter Semester Number]
Institution: NSBM Green University
Degree: BSc (Hons) in Data Science
