🧾 README – CUSTOMER CHURN PREDICTION (customer-churn-prediction)

📌 Project Overview

-This project analyzes customer behavior to identify factors that influence churn and predict which customers are most likely to leave.
It combines data analysis, visualization, and machine learning to support customer retention strategies.

🎯 Objectives

1.Understand patterns behind customer churn.

2.Build a model to predict at-risk customers.

3.Visualize key churn drivers and retention insights.

📊 Dataset

Source: Churn Modelling Dataset (OpendataBay)

Rows: ~10,000 customers
Key fields: Age, Tenure, Balance, Geography, Credit Score, Estimated Salary, Exited (Churn)

🧠 Tools & Techniques

i)Power BI – data cleaning, dashboards & KPIs

ii)Python (Pandas, Scikit-learn) – churn prediction model

iii)Excel – initial exploration & data summaries

⚙️ Process Summary

1.Cleaned and transformed data (handled nulls, standardized columns).

2.Created dashboards showing churn rate by geography, age, and income group.

3.Trained a logistic regression model to predict churn.

4.Visualized top churn drivers and customer retention insights.

💻 How to Run

1) Clone this repository:

       git clone https://github.com/Mutarura/customer-churn-prediction.git


2) Open notebooks/Churn_Prediction.ipynb in Jupyter or VS Code.

       Install dependencies:

       pip install -r requirements.txt


3) Run the notebook to train and evaluate the model.

4) Open the Power BI file (Customer_Churn.pbix) to view the dashboard.

📈 Key Insights

- Customers with short tenure and lower balances showed higher churn probability.

- Geography and age group strongly influenced retention rates.

- Model achieved ~80% accuracy in predicting churn outcomes.

📂 Structure
customer-churn-prediction/
├── data/
├── notebooks/
├── visuals/
└── README.md

