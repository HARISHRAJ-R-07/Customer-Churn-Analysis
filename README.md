📊 Customer Churn Analysis
Data Science Project | Customer Retention & Churn Insights

🔎 Project Overview
Customer churn is an important business problem for subscription-based companies. When customers cancel their subscriptions, the company loses recurring revenue and may also lose long-term customer value.

In this project, I analyzed customer data to identify patterns associated with customer churn and understand which customer characteristics and behaviors may be linked to customers leaving the service.

The analysis follows a practical data analysis workflow:

Load → Understand → Clean → Analyze Churn → Find Patterns → Visualize → Business Insights

🎯 Business Problem
A subscription company has 10,000 customers. Some customers cancel their subscriptions.

The goal of this project is to:

Understand the overall customer churn rate
Compare churn across different subscription plans
Analyze churn patterns by gender and payment method
Compare customer behavior between churned and retained customers
Investigate whether usage and support problems are associated with churn
Generate actionable business insights for customer retention
📁 Dataset
The dataset contains 10,000 customer records and 10 columns.

Column	Description
Customer_ID	Unique customer identifier
Age	Customer age
Gender	Customer gender
Plan	Subscription plan
Monthly_Fee	Monthly subscription fee
Tenure	Customer tenure
Usage_Hours	Customer usage hours
Support_Tickets	Number of support tickets
Payment_Method	Customer payment method
Churn	Churn status: 0 = retained, 1 = churned
🛠️ Technologies Used
🐍 Python
🐼 Pandas
🔢 NumPy
📈 Matplotlib
📊 Seaborn
📓 Google Colab / Jupyter Notebook
🔄 Analysis Performed
1. Data Understanding
Inspected the first rows
Checked dataset information
Checked data types
Checked missing values
2. Data Cleaning
Checked duplicate records
Removed duplicate records where necessary
3. Churn Analysis
Calculated overall churn rate
Analyzed churn by subscription plan
Analyzed churn by gender
Analyzed churn by payment method
Compared numerical characteristics between churned and retained customers
4. Visual Analysis
The project includes visualizations for:

Customer churn distribution
Churn rate by plan
Usage hours vs churn
Support tickets vs churn
💡 Key Findings
The dataset contains 10,000 customers with no missing values in the analyzed columns.
The overall churn rate in the notebook analysis is 59.86%.
Churn rates across Basic, Standard, and Premium plans are relatively close, with Premium showing the highest rate.
Churned customers have a lower average tenure than retained customers.
Churned customers have lower average usage hours than retained customers.
Churned customers have a higher average number of support tickets than retained customers.
The support-ticket analysis suggests that customers experiencing more support problems show a higher tendency to churn.
🎯 Business Insight
Customers showing signs of dissatisfaction—especially higher support activity and lower engagement—can be identified as potential churn-risk customers.

A company could use these insights to:

Improve customer support response times
Proactively contact customers with repeated support issues
Monitor customers with declining usage
Strengthen customer retention strategies
Develop targeted customer engagement programs
Important: These findings show associations in the analyzed dataset. They should not automatically be interpreted as proof that one factor directly causes churn.

📊 Visualizations
All project plots are available in the plots/ folder.

📂 Project Structure
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.ipynb
├── customer_churn.csv
├── requirements.txt
├── README.md
│
└── plots/
    ├── 01_customer_churn_distribution.png
    ├── 02_churn_rate_by_plan.png
    ├── 03_usage_hours_vs_churn.png
    └── 04_support_tickets_vs_churn.png
🚀 Skills Demonstrated
This project demonstrates practical skills in:

Data Cleaning • Exploratory Data Analysis • GroupBy Analysis • Churn Analysis • Data Visualization • Business Insight Generation • Python • Pandas • NumPy • Matplotlib • Seaborn

👨‍💻 About the Project
This project was completed as part of my Data Science learning journey, with a focus on using Python-based data analysis to understand real-world business problems and generate meaningful insights from customer data.

