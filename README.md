# Bank-Customer-Credit-Card-Analytics-Using-Python

## Project Overview

Banks generate large volumes of customer and credit-card data. Analyzing this data helps identify customer spending patterns, credit behavior, transaction trends, and potential financial risks.

This project uses Python for data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to generate meaningful business insights and recommendations for banking decisions.

## Problem Statement

Raw banking data does not always provide clear insights into customer behavior, financial risk, or business opportunities.

The objective of this project is to analyze customer demographics, income, credit scores, credit limits, spending patterns, transactions, loans, and payment behavior to support customer segmentation, credit-risk monitoring, personalized offers, and customer retention.

## Project Objectives

- Analyze customer demographics and financial profiles.
- Identify high-spending customer segments.
- Compare credit-card spending across age groups and card types.
- Analyze city-wise transaction activity.
- Explore relationships between annual income, credit scores, credit limits, and monthly spending.
- Examine credit utilization and payment behavior.
- Identify potential business opportunities and financial risks.
- Provide data-driven recommendations for banking decisions.

## Domain

Banking and Financial Analytics

## Dataset Information

- **Dataset size:** 1,000 customer records
- **Number of columns:** 26
- **Source:** Web-scraped banking and credit-card customer data, collected and compiled for this project.
- **Data format:** CSV

### Dataset Features

| Category | Columns |
|---|---|
| Customer Demographics | customer_id, age, gender, marital_status, education, occupation, city |
| Banking Information | account_type, account_balance, years_with_bank |
| Financial Profile | annual_income, credit_score |
| Credit Card Details | num_credit_cards, credit_limit, card_type |
| Spending Behavior | monthly_spend, num_transactions, avg_transaction_amount, cash_withdrawal, online_spend |
| Credit Risk and Loans | late_payments, loan_status, loan_amount, payment_status, credit_utilization_pct |
| Customer Segmentation | customer_segment |

## Tools and Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Jupyter Notebook / Google Colab** – Development environment
- **Power BI** – Dashboard development using the cleaned dataset

## Project Workflow

### 1. Data Loading and Exploration

- Imported the dataset using Pandas.
- Examined the first and last records using `head()` and `tail()`.
- Checked dataset structure using `info()`.
- Reviewed column names, data types, and dimensions.
- Generated descriptive statistics using `describe()`.

### 2. Data Cleaning and Preprocessing

- Identified missing values using `isnull().sum()`.
- Checked duplicate records using `duplicated().sum()`.
- Filled missing numerical values in annual_income, credit_score, and monthly_spend using their respective medians.
- Filled missing categorical values in education, occupation, and city using their respective modes.
- Verified that the cleaned dataset contained no missing values or duplicate rows.

### 3. Exploratory Data Analysis (EDA)

- Analyzed customer demographics and account types.
- Examined distributions of financial variables.
- Calculated skewness and kurtosis.
- Detected potential outliers using the Interquartile Range (IQR) method.
- Compared spending patterns across customer segments and card types.
- Investigated relationships between income, credit limits, credit scores, and spending.
- Examined credit utilization and payment behavior.

### 4. Data Visualization

Created visualizations using Matplotlib and Seaborn, including:

- Bar plots
- Horizontal bar plots
- Point plots
- Scatter plots
- Regression plots
- Histograms and distribution plots
- Box plots
- Correlation heatmaps
- Pair plots
- Grouped count plots

### 5. Business Insights and Recommendations

Used the analysis results to identify high-spending segments, transaction patterns, financial relationships, and areas requiring further credit-risk investigation.

### 6. Power BI Integration

Exported the cleaned dataset to CSV for use in Power BI dashboard development.

## Key Findings

### 1. Customer Segmentation

- Premium customers recorded the highest average monthly spending at approximately 90,939.
- Mass Affluent customers recorded average monthly spending of approximately 40,434.
- Basic and Standard customers had lower average monthly spending than the other segments.

### 2. Spending by Card Type

- Signature cardholders recorded the highest average monthly spending at approximately 36,826.
- Classic cardholders followed at approximately 36,094.
- Platinum and Gold cardholders recorded average monthly spending of approximately 35,308 and 34,859, respectively.

### 3. Geographic Analysis

- Pune had the highest customer count among the displayed cities, with 119 customers.
- Ahmedabad followed with 114 customers.
- City-level transaction analysis can help identify regional customer engagement opportunities.

### 4. Income and Credit Limit

- Annual income and credit limit showed a strong positive correlation of approximately **0.84**.
- This indicates that higher annual income was associated with higher credit limits in the analyzed dataset.
- Income alone is not sufficient to determine credit eligibility.

### 5. Customer Spending Behavior

- The average monthly spending across the dataset was approximately 35,659.
- Total online spending was approximately 18.58 million.
- The average transaction amount was approximately 2,108.
- Spending patterns varied across customer segments, ages, and card types.

### 6. Credit Utilization and Payment Behavior

- Average credit utilization was approximately 13.91%.
- The report identified payment delays as an area for further investigation.
- Customers with repeated late payments or high credit utilization may require additional review and suitable repayment support.

*Note: These findings describe the analyzed dataset. They should not be interpreted as proof of causation or as a guarantee of future customer behavior.*

## Business Recommendations

### 1. Customer Retention

Develop personalized rewards, cashback programs, and suitable banking services for valuable customer segments.

### 2. Credit-Limit Management

Consider credit-limit reviews using income, credit score, repayment history, outstanding debt, affordability, and responsible lending criteria.

### 3. Credit-Risk Monitoring

Monitor repeated late payments, high credit utilization, and other relevant financial indicators to identify accounts requiring further assessment.

### 4. Targeted Marketing

Use customer segment, spending behavior, and card type to design relevant credit-card offers.

### 5. Geographic Strategy

Use city-level transaction activity to guide regional marketing campaigns and customer engagement initiatives.

### 6. Data-Driven Decisions

Use statistical analysis and visualizations to understand relationships between financial variables and support evidence-based banking decisions.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Missing Value Treatment
- Outlier Detection using IQR
- Data Visualization
- Correlation Analysis
- Customer Segmentation
- Business Insight Generation
- Python and Pandas
- Power BI Data Preparation

## Project Outcome

This project demonstrates how Python-based data analytics can transform raw banking data into meaningful business insights.

The analysis helps explore customer spending behavior, financial relationships, transaction activity, and potential credit-risk indicators. The findings can support customer segmentation, targeted marketing, responsible credit management, and improved customer engagement.

## Conclusion

The Bank Customer & Credit Card Analytics project combines data cleaning, exploratory analysis, statistical techniques, and visualization to understand banking customer behavior.

The project also demonstrates the value of integrating Python analysis with Power BI dashboards to communicate findings clearly and support data-driven business decisions.

## Author

**Idaya Gracy Jude**

Aspiring Data Analyst | Python | SQL | Power BI | Excel


---

*This project was developed for data analytics learning and portfolio demonstration. The findings are based on the dataset analyzed and are not intended to replace formal banking or credit-risk assessment procedures.*
