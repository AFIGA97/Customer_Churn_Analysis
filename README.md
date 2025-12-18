Customer Churn Analysis & Prediction

🚀 Overview

This project focuses on predicting telecom customer churn using real-world subscription, billing, and demographic data. The notebook walks through data preprocessing, exploratory data analysis, customer segmentation, model building, evaluation, and business recommendations.​

📂 Features

Data loading, cleaning, and preprocessing (handling missing values, type conversion, encoding).​

Exploratory Data Analysis (EDA) on tenure, charges, contracts, and services vs churn.​

Customer segmentation by tenure_group, charge_group, and Contract with churn rate per segment.​

Machine learning model for churn prediction using Logistic Regression (and extendable to other models).​

Evaluation using accuracy, precision, recall, F1-score, and ROC–AUC with ROC curve visualization.​

Business insights and retention strategy recommendations based on model and segment analysis.​

🗃️ Dataset

File: telco_customer_churn.csv (or your dataset name).

Each row represents a customer, including:

Demographics: gender, senior citizen, partner, dependents.

Services: phone, internet, streaming, security, backup, tech support, etc.

Billing & contract: tenure, contract type, payment method, monthly and total charges.

Target: Churn (Yes/No), later encoded as 1/0.​

⚙️ Installation & Usage

Clone or download the repository:

bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Place the churn dataset (e.g., telco_customer_churn.csv) inside the project folder or data/ directory.​

Install dependencies:

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Open Customer_churn_analysis_prediction.ipynb in Jupyter Notebook or Google Colab.

Run all cells to execute data loading, preprocessing, EDA, segmentation, modeling, and evaluation.

Review churn rates by segment, classification metrics, and ROC curve plots to interpret model performance and business impact.​

🛠️ Dependencies

numpy

pandas

matplotlib

seaborn

scikit-learn​

📈 Results

Overall churn rate computed and visualized across different demographic and service groups.​

Segmentation tables showing churn rate and customer counts for combinations of tenure_group, charge_group, and Contract (highlighting highest-risk segments like month-to-month, high charges, low tenure).​

Trained Logistic Regression model evaluated on a test set with metrics such as accuracy, precision, recall, F1-score, and ROC–AUC, plus ROC curve visualization.​

Key drivers of churn identified through feature patterns and segment behavior, supporting targeted retention strategies.​


👤 Credits

Created by AFIGA BEGUM.A as part of the Saiket Systems Data Science internship, focusing on applying machine learning to real-world customer churn prediction.​​
📧 Email: afiga97@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/afigabegum
