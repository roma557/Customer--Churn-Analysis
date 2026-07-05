Customer churn is one of the biggest challenges for subscription-based businesses. Understanding why customers leave helps companies improve customer satisfaction and increase long-term revenue.

This project performs **Exploratory Data Analysis (EDA)** on the **Telco Customer Churn Dataset** to identify patterns, trends, and factors that contribute to customer churn.

The analysis includes data cleaning, preprocessing, visualization, and business insights using Python.

---

# 🎯 Objectives

- Analyze customer demographics and subscription behavior.
- Identify the major factors influencing customer churn.
- Discover trends using data visualization.
- Generate actionable business recommendations to reduce churn.

---

# 📂 Dataset Information

| Feature | Details |
|---------|----------|
| Dataset | Telco Customer Churn |
| Records | 7,043 Customers |
| Features | 21 Columns |
| Target Variable | Churn |

### Dataset includes:

- Customer Demographics
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📊 Data Cleaning

The following preprocessing steps were performed:

- Removed missing values
- Converted data types
- Cleaned TotalCharges column
- Checked duplicate records
- Verified null values
- Prepared data for visualization

---

# 📈 Exploratory Data Analysis

The project includes visual analysis of:

- Customer Churn Distribution
- Gender Distribution
- Senior Citizen Analysis
- Tenure Analysis
- Contract Type
- Internet Service
- Phone Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Payment Method
- Monthly Charges Distribution
- Total Charges Distribution

Visualizations used:

- Count Plot
- Pie Chart
- Histogram
- Box Plot
- Distribution Plot
- Subplots

---

# 📌 Key Insights

## Customer Churn

- **73.46%** of customers stayed with the company.
- **26.54%** of customers churned.

This indicates that approximately **1 out of every 4 customers** leaves the service.

---

## Customer Tenure

- Customers with shorter tenure have the highest churn rate.
- Long-term customers are significantly more loyal.

---

## Contract Type

- Month-to-Month contracts show the highest churn.
- One-Year and Two-Year contracts retain customers more effectively.

---

## Internet Service

- Fiber Optic users have a higher churn rate compared to DSL users.

---

## Additional Services

Customers without:

- Online Security
- Online Backup
- Device Protection
- Tech Support

show considerably higher churn.

---

## Payment Method

Customers using **Electronic Check** experience the highest churn rate.

Customers using automatic payment methods demonstrate better customer retention.

---

# 💼 Business Recommendations

Based on the analysis, the following strategies are recommended:

- Encourage customers to upgrade to long-term contracts.
- Improve onboarding for new customers.
- Promote bundled services such as Online Security and Tech Support.
- Investigate customer experience issues related to Fiber Optic services.
- Offer incentives for automatic payment methods.
- Develop targeted retention campaigns for high-risk customer groups.
