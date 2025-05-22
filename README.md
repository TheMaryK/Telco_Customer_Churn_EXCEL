# Churn Risk Profiling for Smarter Retention in Telecom Customers

![TEL](https://github.com/user-attachments/assets/f68b4bf0-9e5d-4bf9-9630-e2db07092fc4)

# INTRODUCTION
This analysis identified the key characteristics of high-risk churn customers in a telecom dataset, revealing specific patterns in demographics, service usage, and billing behavior. These insights emphasize the need for targeted retention strategies such as personalized service offerings, improved payment flexibility, and longer-term contracts which are all critical for reducing churn and boosting customer satisfaction.

# CENTRAL INSIGHTS

Customers who are **female**, **non-senior**, **single**, **independent**, **on a month-to-month contract**, **paying via electronic check**, **with a short tenure (1-12 months)**, and **using fewer services (1-5)** exhibit the **highest churn rates**.

# TASK

1. Analyze churn distribution across demographics.
2. Examine the relationship between churn and contract types, payment methods, tenure, and service usage.
3. Identify key trends using visualizations.
4. Design a light-themed dashboard in Excel to display key insights visually.
5. Incorporate interactive filters, key insights & recommendations into the dashboard.

# TOOLS USED

**Excel** – Data cleaning, analysis, visualization and dashboard creation

**GitHub**  – Project documentation and version control

# SKILLS DEMONSTRATED

**Data Cleaning & Preparation** – Formatting inconsistencies, craeting new calculated columns and ensuring data accuracy.

** Analysis ** – Identifying patterns, trends, and correlations in churn behavior.

**Data Visualization** – Creating impactful charts and dashboards for effective storytelling.

**Critical Thinking & Problem-Solving** – Interpreting data insights to drive actionable recommendations.

**Dashboard Design** – Structuring data visualizations for clear communication of insights.

# ABOUT THE DATASET

The dataset consists of:
21 columns
7,044 rows
Covers customer data and the dataset includes details like Customer ID, gender, age, tenure, dependent, partner and the services rendered by the telecommunication company. [Download here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

# SUMMARY OF WORK DONE

## Data Preprocessing

- No duplicates
- No missing values
- Created new columns to derive additional insights
   1.	Age Group (using the SeniorCitizen column)                                         
  2.	Marital Status (using the Partner column)
  3.	Household Type (using the dependents column)
  4.	Churned - This helps to change the column into a binomial format (using the Churn column)
  5.	Service Count (using the Services column)
![Screenshot 2025-04-22 140032](https://github.com/user-attachments/assets/2324df5e-c8e8-46c8-a97a-951e3350d3a8)


## FINDINGS

![Screenshot 2025-04-22 135552](https://github.com/user-attachments/assets/66fc42f9-a72f-47f6-a0bf-19ee70292848)


- Females, Senior citizens & customers without partners and dependents are more likely to churn.

- Customers on month-to-month contracts churn at significantly higher rates compared to those on one-year or two-year contracts.

- Customers who use electronic checks as a payment method show the highest churn rates compared to those using automatic bank transfers or credit cards.

- More than 55% of churn occurs within the first 1-12 months of tenure, indicating that early retention efforts are crucial.

- Customers who pay higher monthly charges are more likely to churn, suggesting price sensitivity.


## Recommendations

- Incentives like discounted rates or loyalty rewards to transition customers should be offered from month-to-month plans to annual contracts.

- Incentives for customers to switch from electronic checks to more stable payment options like auto-debit bank transfers should also be provided.

- Personalized onboarding programs,  early engagement campaigns, and customer support touchpoints  should be implemented within the first 12 months.

- Tiered pricing plans or bundled discounts should be offered to prevent churn among high-paying customers.

- Personalized marketing & loyalty programs should also be explored to retain senior citizens, independent customers, and those with high churn risk.


![2025](https://github.com/user-attachments/assets/52c80e5a-7006-4267-9e77-faa7491d33d3)


