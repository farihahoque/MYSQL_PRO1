# # Telco Customer Churn Analysis using MySQL

## Overview

This project explores the factors contributing to customer churn within a fictional telco company based on data provided for Q3 in California. The analysis leverages MySQL to clean, transform, and explore the dataset, aiming to identify key drivers of churn and provide insights that could inform customer retention strategies.

## 📁 Project Structure

- `Data Cleaning`: SQL queries used to clean the raw data (handle nulls, fix types, format fields, etc.).Here we removed duplicates, null, blank values and unnecessary column.
- `Data Exploration`:his file contains the SQL queries used to perform exploratory data analysis (EDA) on the cleaned dataset. This includes investigating relationships between different variables and the churn outcome.
- `README.md`: This file provides Project overview, objectives, and results.

## Dataset

The dataset used for this analysis is the "Telco Customer Churn" dataset, which contains information on 7043 customers, including demographics, service usage, contract details, satisfaction scores, and churn status. The key fields in the dataset include:

* `CustomerID`: Unique identifier for each customer.
* `Churn`: Indicates whether the customer churned ('Yes' or 'No').
* `Contract`: The type of contract the customer has (e.g., Month-to-month, One year, Two year).
* `InternetService`: The customer's internet service provider (e.g., DSL, Fiber optic).
* `MonthlyCharge`: The customer's current total monthly charge for all their services.
* `Tenure in Months`: The total amount of months that the customer has stayed with the company.
* `SatisfactionScore`: Customer's self-reported satisfaction score.
* `ChurnReason`: The reason provided by the customer for churning.

## Exploratory Analysis Questions Addressed

1.  What is the overall churn rate in the dataset?
2.  How does churn rate vary across different Age groups?
3.  How does churn rate vary across different customer statuses?
4.  What is the distribution of churn by gender and marital status?
5.  How much revenue was lost to churned customers?
6.  Do geographic patterns relate to churn?
7.  What is the average CLTV for churned and non-churned customers?
8.  What are the general reasons for churn and its categories?
9.  How does Churn Score relate to churn?
10. How do types of internet service (DSL, Fiber Optic, None) and internet type influence churn?
11. How does contract type impact on churn?
12. What is the Satisfaction score correlation with churn?
13. What type of offers do churners have?
14. What is the churn rate by PaymentMethod?
15.  What’s the impact of entertainment services on churn?
16.  What is the relation of high-value customers to churning?

## Findings and Insights






