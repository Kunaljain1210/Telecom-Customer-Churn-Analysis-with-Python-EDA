📞 Telecom Customer Churn Analysis using Python (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the IBM Telco Customer Churn dataset to identify the key factors influencing customer churn and uncover actionable business insights. The analysis focuses on understanding customer demographics, contract types, subscribed services, payment methods, tenure, and account information to determine the primary drivers of customer attrition.

The project was developed using Python and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn to perform data cleaning, visualization, and business-oriented analysis.

🎯 Objective

The primary objectives of this project are to:

Analyze customer demographics and their impact on churn.
Identify the major factors contributing to customer attrition.
Understand customer behavior across different contract types and subscribed services.
Examine the relationship between tenure, monthly charges, and churn.
Discover high-risk customer segments.
Generate actionable business insights to improve customer retention.
📂 Dataset Information
Dataset: IBM Telco Customer Churn
Total Records: 7,043
Total Features: 21
Important Features
CustomerID – Unique customer identifier
Gender – Male/Female
SeniorCitizen – Indicates whether the customer is a senior citizen
Partner – Customer has a partner or not
Dependents – Customer has dependents or not
Tenure – Number of months the customer has stayed
PhoneService – Phone service subscription
InternetService – Type of internet service
OnlineSecurity – Online security subscription
TechSupport – Technical support subscription
StreamingTV – Streaming TV subscription
Contract – Contract type
PaymentMethod – Customer payment method
MonthlyCharges – Monthly bill amount
TotalCharges – Total amount charged
Churn – Customer churn status
🛠️ Project Workflow
1️⃣ Data Cleaning
Removed unnecessary columns.
Checked for duplicate records.
Handled missing values.
Corrected data types.
Converted numerical columns into appropriate formats.
Performed data validation before analysis.
2️⃣ Exploratory Data Analysis (EDA)
👥 Customer Demographics
Analyzed churn based on gender, senior citizens, partners, and dependents.
Compared customer retention across demographic groups.
📄 Contract Analysis
Studied churn behavior across Month-to-Month, One-Year, and Two-Year contracts.
Identified contract type as one of the strongest indicators of churn.
⏳ Customer Tenure Analysis
Explored customer lifespan using tenure distribution.
Compared tenure between churned and retained customers.
💳 Payment Method Analysis
Evaluated customer churn across different payment methods.
Identified payment methods associated with higher churn.
📞 Service Subscription Analysis

Analyzed customer behavior for services including:

Phone Service
Multiple Lines
Internet Service
Online Security
Online Backup
Device Protection
Tech Support
Streaming TV
Streaming Movies
💰 Billing Analysis
Compared Monthly Charges and Total Charges across churn categories.
Examined spending patterns of retained and churned customers.
📊 Correlation Analysis
Generated correlation heatmaps for numerical variables.
Identified relationships between customer tenure, charges, and churn.
📊 Data Visualizations

The project includes multiple business-oriented visualizations such as:

📈 Count Plots
📊 Bar Charts
📦 Box Plots
📉 Histograms
🔥 Correlation Heatmaps
📍 Distribution Plots
📊 Pie Charts
📋 Stacked Bar Charts
📈 Customer Segmentation Visualizations
🔍 Key Insights
📌 Customer Churn
Approximately 26.5% of customers have churned, while the majority continue using the company's services.
📄 Contract Type
Customers with Month-to-Month contracts exhibit the highest churn rate.
Long-term contracts significantly improve customer retention.
⏳ Customer Tenure
Customers with shorter tenure are more likely to churn.
Long-term customers demonstrate significantly higher loyalty.
👥 Customer Demographics
Senior citizens show a comparatively higher churn rate than non-senior customers.
Gender has minimal influence on customer churn.
📞 Service Adoption
Customers subscribed to services such as Online Security, Tech Support, and Device Protection generally show better retention.
Customers without these value-added services are more likely to leave.
💳 Payment Method
Customers using Electronic Check have the highest churn among all payment methods.
💰 Billing Pattern
Customers paying higher monthly charges tend to churn more frequently than customers with lower monthly bills.
📚 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
🚀 Skills Demonstrated
Data Cleaning
Data Wrangling
Exploratory Data Analysis (EDA)
Statistical Analysis
Data Visualization
Business Insight Generation
Customer Segmentation
Correlation Analysis
Business Storytelling
📌 Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand customer behavior and identify the key factors driving customer churn. By analyzing customer demographics, tenure, contract types, subscribed services, payment methods, and billing information, the project uncovers meaningful patterns that can support strategic business decisions.

The insights generated from this analysis suggest that customer retention can be improved by promoting long-term contracts, encouraging the adoption of value-added services, and implementing targeted retention strategies for high-risk customer segments. Overall, this project showcases the complete Data Analyst workflow—from data cleaning and visualization to extracting actionable business insights that help organizations make informed, data-driven decisions.

⭐ If you found this project useful, consider giving it a Star!
