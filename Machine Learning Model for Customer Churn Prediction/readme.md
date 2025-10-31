Project 2: Customer Churn Prediction (Machine Learning Project)
📄 Overview

This project aims to predict customer churn for a telecom company using Machine Learning techniques.
It helps identify customers likely to leave and allows businesses to take preventive retention actions.

💼 Objectives

Analyze customer behavior patterns.

Build a predictive model to forecast churn.

Generate actionable business insights.

🧩 Dataset

Name: Telco Customer Churn Dataset

Records: 7,043

Features: 21 columns (Customer details, services, charges, churn)

Source: Kaggle

🧰 Tools & Libraries Used

Python 🐍

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (Logistic Regression)

Jupyter Notebook

⚙️ Steps Performed

Data Cleaning – handled missing values and converted TotalCharges to numeric.

Exploratory Data Analysis (EDA) – visualized churn by gender, internet type, contract type, etc.

Feature Encoding – used LabelEncoder to convert categorical variables.

Model Training – trained Logistic Regression model.

Evaluation – measured accuracy, confusion matrix, and classification report.

Dashboard Visualization – created detailed churn insights using Matplotlib and Seaborn.

📊 Model Performance
Metric	Score
✅ Accuracy	0.815 (81.5%)
Precision (Non-Churn)	0.86
Recall (Non-Churn)	0.90
Precision (Churn)	0.68
Recall (Churn)	0.58
F1-Score (Overall)	0.81

Confusion Matrix:

[[934 102]
 [158 215]]

📈 Key Visualizations

Churn Distribution

Gender vs Churn

Internet Service vs Churn

Contract Type vs Churn

Correlation Heatmap

📸 (Add graph images here after uploading to GitHub)

![Churn Distribution](images/churn_distribution.png)
![Contract Type vs Churn](images/contract_vs_churn.png)

💡 Insights

Customers with month-to-month contracts are most likely to churn.

Fiber optic internet users show higher churn.

Customers with longer tenure are less likely to leave.

🧠 Future Improvements

Try Decision Tree, Random Forest, or XGBoost for higher accuracy.

Create an interactive Power BI dashboard for management.

Deploy this model using Streamlit or Flask as a live web app.

👨‍💻 About Me

Syed Ahmed — Data Analyst | Power BI | Machine Learning | Python
📧 Email: syedahmed.sa43@gmail.com

🌐 GitHub: github.com/SyedAhmed7860

💼 LinkedIn: linkedin.com/in/syedahmedpro

⚖️ License

This project is licensed under the MIT License — feel free to use and modify with credit.
