# TELCO CUSTOMER CHURN ANALYSIS

![telco 2](https://github.com/user-attachments/assets/851f1051-69a9-4b83-b621-29ea5552e510)

# INTRODUCTION

This analysis effectively identified the **primary drivers of customer churn** in the telecom dataset. The insights gathered emphasize the need for targeted retention strategies, implementing personalized service offerings, improving payment flexibility, and fostering long-term contracts can significantly reduce churn and enhance customer satisfaction.

# CENTRAL INSIGHTS

Customers who are **female**, **non-senior**, **single**, **independent**, **on a month-to-month contract**, **paying via electronic check**, **with a short tenure (1-12 months)**, and **using fewer services (1-5)** exhibit the **highest churn rates**.

# TASK

1. Analyze churn distribution across demographics.
2. Examine the relationship between churn and contract types, payment methods, tenure, and service usage.
3. Identify key trends using visualizations.
4. Design a dark-themed dashboard in Excel to display key insights visually.
5. Incorporated interactive filters, Key Insights & Recommendations into the dashboard.

# TOOLS USED

**Excel** – Data cleaning, analysis, and dashboard visualization

**GitHub**  – Project documentation and version control

# SKILLS DEMONSTRATED

**Data Cleaning & Preparation** – Formatting inconsistencies, craeting new calculated columns and ensuring data accuracy.

**Exploratory Data Analysis (EDA)** – Identifying patterns, trends, and correlations in churn behavior.

**Data Visualization** – Creating impactful charts and dashboards for effective storytelling.

**Critical Thinking & Problem-Solving** – Interpreting data insights to drive actionable recommendations.

**Dashboard Design** – Structuring data visualizations for clear communication of insights.

# DATA SOURCE

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

It has 7044 columns and 21 rows. 

# SUMMARY OF WORK DONE

## Data Preprocessing
- No duplicates
- No missing values
- Created new columns to derive additional insights
   1.	Age Group (using the SeniorCitizen column)
  ```excel
     (=IF([@SeniorCitizen]=1, "Senior", "Other")
  ```                                                
  2.	Marital Status (using the Partner column)
  ```excel
  (=IF([@Partner]="Yes", "With partner", "No partner")
  ```
  3.	Household Type (using the dependents column)
  ```excel
  (=IF([@Dependents]="Yes", "Has Dependents", "Independent")
  ```
  4.	Churned - This helps to change the column into a binomial format (using the Churn column)
  ```excel
  (=IF([@Churn]="Yes", 1,0)
  ```
  5.	Service Count (using the Services column)
  ```excel
  (=COUNTIF(G107:O107, "Yes")
  ```

![Screenshot 2025-03-13 141006](https://github.com/user-attachments/assets/bf392286-e895-43a7-930e-3907687905bf)

## KEY INSIGHTS

- Females, Senior citizens & customers without partners and dependents are more likely to churn.

- Customers on month-to-month contracts churn at significantly higher rates compared to those on one-year or two-year contracts.

- Customers who use electronic checks as a payment method show the highest churn rates compared to those using automatic bank transfers or credit cards.

- More than 55% of churn occurs within the first 1-12 months of tenure, indicating that early retention efforts are crucial.

- Customers who pay higher monthly charges are more likely to churn, suggesting price sensitivity.


## Recommendations
- Offer incentives like discounted rates or loyalty rewards to transition customers from month-to-month plans to annual contracts.

- Provide incentives for customers to switch from electronic checks to more stable payment options like auto-debit bank transfers.

- Implement personalized onboarding programs,  early engagement campaigns, and customer support touchpoints within the first 12 months.

- Offer tiered pricing plans or bundled discounts to prevent churn among high-paying customers.

- Use personalized marketing & loyalty programs to retain senior citizens, independent customers, and those with high churn risk.
  

## Dashboard

![Screenshot 2025-03-13 151727](https://github.com/user-attachments/assets/9dac945b-9eeb-4184-8b25-55952f6ba160)


![2025](https://github.com/user-attachments/assets/52c80e5a-7006-4267-9e77-faa7491d33d3)


