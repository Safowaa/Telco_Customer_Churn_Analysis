  # Telco Customer Churn Analysis
Customer churn, the phenomenon where customers stop using a company's product or service, is a critical issue for many businesses. Retaining customers is often more cost-effective than acquiring new ones, making churn prediction an essential task for companies looking to improve customer loyalty and increase profitability.



## Project Overview

This project aims to analyze customer churn data from a telecommunications company. The analysis includes Exploratory Data Analysis (EDA), addressing business questions through visualizations, the objective of this project is to build a predictive model that can accurately identify customers who are likely to churn. This model will help the company take proactive measures to retain high-risk customers.

## Table of Contents

- [Introduction](#introduction)
- [Data Description](#data-description)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Business Questions and Visualizations](#business-questions-and-visualizations)
- [Machine Learning Model](#machine-learning-model)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)

## Introduction

Customer churn is a critical issue for telecom companies as it directly impacts revenue. This project involves understanding the factors that contribute to customer churn and building a predictive model to help the company take proactive measures to retain customers.

## Data Description

The dataset used in this project contains various attributes of customers, including:

- CustomerID
- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn (target variable)

## Exploratory Data Analysis (EDA)

EDA was performed to understand the distribution of data, detect anomalies, and identify relationships between features. Key findings include:

- Distribution of customers based on tenure, monthly charges, and contract type.
### EDA Visualization
![Monthly Charges](Visuals\churn_by_contract_type.png)

![Number of Months](Visuals\Tenure_by_churn.png)

![Senior Citizen](Visuals\churn_by_seniorCitizen.png)

- Correlation between different features and their impact on churn.

![Correlation HeatMap](Visuals\correlation_numeric.png)

## Business Questions and Visualizations

Several business questions were asked and answered through visualizations:

### PowerBI Dashboard 
![Telco Churn Analysis Dashboard](Visuals\Dashboard.png)

1. **How does customer churn vary across different genders??**
   ![Churn to Genders](Visuals\churn_by_gender.png)
   
2. **What impact do different service offerings have on customer churn?**
   ![Service to Churn](Visuals\Service_to_Churn.png)
   
3. **How effective are customer support interactions in reducing churn?**
   ![Customer support to Churn](Visuals\churn_by_contract_type.png).

4. **What are the reasons behind the differences in churn rates among various contract types?**
   ![Churn to Contract Type](Visuals\Churn_to_Contract_Type.png).
## Machine Learning Model

A machine learning model was built to predict customer churn on the test data. The process involved:

- Data preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
- Model selection: Evaluated multiple models including Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting. The best model is Logistic Regression model 
- Model evaluation: Used metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.

The best-performing model was chosen based on these evaluation metrics and used to predict the churn column in the test data.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Safowaa/Telco_Customer_Churn_Analysis.git



## Conclusion

This project provided valuable insights into the factors influencing customer churn in the telecom industry. The predictive model can be used by the company to identify customers at risk of churning and take proactive measures to retain them.

## Recommendations

- Focus on improving customer support interactions to reduce churn rates.

- Pay attention to the service offerings that have higher churn rates and explore ways to improve them.

- Consider offering incentives or benefits for long-term contracts to reduce churn rates.

## References

- Visit [Link](https://app.powerbi.com/groups/me/reports/a814a603-ddbe-4f36-8c6e-674ecd59f05b/ReportSection?experience=power-bi) to interact with the dashboard of this project.

- Visit [Link](https://medium.com/@safowaabenedicta/telco-customer-attrition-analysis-faae3476c6fb) to read article.



 
