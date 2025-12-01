# Customer Churn Analysis

## Project Overview
A comprehensive exploratory data analysis (EDA) on telecom customer churn data to identify key factors behind customer loss and provide actionable business recommendations.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Detailed Analysis](#detailed-analysis)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Author & Contact](#author--contact)

## Problem Statement
Telecom companies lose a lot of money when customers stop using their services and move to other providers. Since getting new customers is much more expensive than keeping existing ones, it is important to understand the reasons behind customer churn.

This project analyzes customer details such as their plans, services used, and billing information to find out:
- **Who** is most likely to leave?
- **Why** are they leaving?
- **What** can the company do to make them stay?

The goal is to help the business make better decisions to reduce churn, improve customer satisfaction, and prevent revenue loss.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **IDE:** Jupyter Notebook

## Dataset

| Attribute | Details |
|-----------|---------|
| **Records** | 7,043 customers |
| **Features** | 21 columns |
| **Target** | Churn (Yes/No) |
| **Source** | Telecom Customer Data |

### Key Features
- **Demographics:** Gender, Senior Citizen, Partner, Dependents
- **Services:** Phone, Internet, Security, Backup, Support, Streaming
- **Billing:** Contract Type, Payment Method, Monthly & Total Charges
- **Target:** Churn Status

## Project Structure
```
Customer_Churn_Analysis/
|
├── Dataset/
│   └── customer_churn_data.csv
|
├── Images/
│   └── Churn by Contract.png
│		└── Churn by Dependents.png
│		└── Churn by DeviceProtection.png
│		└── Churn by InternetService.png
│		└── Churn by MonthlyCharges.png
│		└── Churn by OnlineBackup.png
│		└── Churn by OnlineSecurity.png
│		└── Churn by PaperlessBilling.png
│		└── Churn by Partner.png
│		└── Churn by PaymentMethod.png
│		└── Churn by SeniorCitizen.png
│		└── Churn by TechSupport.png
│		└── Churn by tenure.png
│		└── Churn by TotalCharges.png
│		└── Churn vs Non-Churn Customer Count.png
│		└── Relationship Between Numerical Features.png
│
├── Notebooks/
│   └── customer_churn_eda.ipynb
|
├── Requirements.txt
|
├── README.md
```

## Detailed Analysis

#### [View Full Notebook](https://github.com/RajanKumar-787/Customer_Churn_Analysis_Python/blob/0782da947ba165d263876f19f0ab8685978352f2/Notebooks/customer_churn_eda.ipynb)

The complete analysis, including code, visualizations, and step-by-step explanations, is available in the Jupyter notebook. It covers:

1. **Data Cleaning & Preprocessing**
- Converted data types and standardized categorical fields
- Handled 11 missing values in `TotalCharges`
- Removed invalid customer records (tenure = 0)

2. **Exploratory Data Analysis**
- Created 15+ visualizations across major features
- Generated KDE plots for numerical features
- Built Count plots for categorical features
- Developed a comprehensive correlation heatmap

3. **Feature-Level Insights**
- Identified several high-risk customer segments based on tenure, contract type, service usage, and customer demographics

4. **Business Recommendations**
- Translated analytical findings into actionable recommendations
- Clarified why specific customer groups churn more frequently
- Provided context to support strategic decision-making

## Key Insights

| Factor | High Churn Group | Low Churn Group |
|--------|------------------|-----------------|
| **Tenure** | 0-12 months | 48+ months |
| **Monthly Charges** | $70-100 | Below $40 |
| **Contract** | Month-to-month | One-year or Two-year |
| **Internet Service** | Fiber optic | DSL or No internet service |
| **Payment Method** | Electronic check | Auto-pay (Bank transfer or Credit card) |
| **Add-on Services** | Without security/support | With security/support |
| **Demographics** | Senior citizens, No partner | Non-seniors, With partner |

## Business Recommendations

1. **Focus on New Customers:** Give welcome offers, do regular check-ins, and provide quick support so they don't leave early.

2. **Promote Long-Term Contracts:** Offer discounts, loyalty rewards, and bundle pricing for yearly contracts.

3. **Move Customers to Auto-Pay:** Reward customers who set up auto-pay with bank or credit card.

4. **Offer Service Bundles:** Create package deals (Internet + Security + Support) so customers get more value and won't switch easily.

5. **Support Senior Citizens:** Provide special pricing and dedicated support for senior citizens.

6. **Improve Fiber Optic Services:** Identify and resolve service quality issues, ensure competitive pricing, and provide better customer support for fiber users.

## Author & Contact

**Author:** Rajan Kumar  
**Email:** rajaninranchi787@gmail.com  
**GitHub:** [https://github.com/RajanKumar-787](https://github.com/RajanKumar-787)  
**LinkedIn:** [https://www.linkedin.com/in/rajankumar787/](https://www.linkedin.com/in/rajankumar787/)  

⭐ If you found this project helpful, please consider giving it a star!  
💬 Feedback and suggestions are always welcome!

