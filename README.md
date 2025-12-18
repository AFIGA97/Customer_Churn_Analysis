#  Customer Churn Analysis & Prediction

## 🚀 Overview
This project predicts telecom customer churn using real-world demographic, service, and billing data. It covers data preprocessing, exploratory data analysis (EDA), customer segmentation, model building, evaluation, and business-focused insights.

## 📂 Key Features
- Data cleaning and preprocessing (missing values, type conversion, encoding).
- EDA on tenure, charges, contracts, services, and demographics vs churn.
- Customer segmentation using `tenure_group`, `charge_group`, and `Contract` to find high-risk segments.
- Churn prediction model using Logistic Regression.
- Evaluation with accuracy, precision, recall, F1-score, and ROC–AUC plus ROC curve.

## 🗃️ Dataset
- Telecom customer churn dataset (e.g., `telco_customer_churn.csv`).
- Features include demographics (gender, senior citizen, partner, dependents), services (phone, internet, streaming, security, backup, tech support), and billing (contract, payment method, monthly and total charges, tenure).
- Target column: `Churn` (Yes/No, encoded to 1/0).

## ⚙️ Installation & Usage
-git clone https://github.com/AFIGA97/Customer_Churn_Analysis.git
-cd Customer_Churn_Analysis
-pip install pandas numpy matplotlib seaborn scikit-learn

- Place the dataset CSV in the project folder.
- Open `Customer_churn_analysis_prediction.ipynb` in Jupyter or Google Colab.
- Run all cells to perform preprocessing, EDA, segmentation, modeling, and evaluation.

## 🛠️ Dependencies
- Python 3.x  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

## 📈 Results & Insights
- Overall churn rate and visual comparisons by contract, tenure groups, and charge levels.
- Segment tables showing churn rate and customer counts by `tenure_group` × `charge_group` × `Contract`.
- Logistic Regression performance reported with classification metrics and ROC–AUC.
- Business recommendations to target short-tenure, high-charge, month-to-month customers and encourage longer-term contracts.

## 👤 Credits
- Author: AFIGA BEGUM.A
- Internship: Data Science Internship at Saiket Systems  
- Email: afiga97@gmail.com
- LinkedIn: https://www.linkedin.com/in/afigabegum

