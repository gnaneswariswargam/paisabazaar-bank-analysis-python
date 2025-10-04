Paisabazaar Banking Fraud Analysis

Project Overview

This is a Complete End-To-End professional project on Paisabazaar Banking Fraud Analysis. It includes step-by-step explanations to complete the whole project from start to finish. The project contains 20 KPIs and 18 charts for visualization.

Project Name: Paisabazaar Banking Fraud Analysis
Project Type: Exploratory Data Analysis (EDA)
Contribution: Individual
Project By: Gnaneswari Swargam

Project Summary

The financial industry has witnessed a rise in fraudulent activities and credit risks over the past decade, making fraud detection and credit risk assessment critical for banks. In this project, we analyze a dataset provided by Paisabazaar, including customer demographics, financial details, credit utilization patterns, and payment behaviors.

By conducting EDA and visualizations, the project aims to uncover insights to detect fraudulent behavior, assess financial risk, and strengthen customer credit profiling.

Dataset size: 81,782 records

Number of attributes: 28

Key features: Annual Income, Monthly In-hand Salary, Number of Bank Accounts, Number of Credit Cards, Interest Rate, Outstanding Debt, Credit Utilization Ratio, Credit History Age, Payment Behavior, Credit Score

The project covers:

Data Cleaning & Preprocessing – handling missing values, duplicates, outliers.

Exploratory Data Analysis (EDA) – investigating relationships between features and financial risk.

Fraud Analysis – detecting suspicious patterns in financial behavior.

Credit Risk Profiling – analyzing factors affecting credit score categories.

Visual Storytelling – using bar charts, histograms, scatter plots, boxplots, heatmaps, and KDE plots to derive insights.

Problem Statement

We are given a dataset of 81,782 banking customers with detailed information about their financial activities, credit history, and personal profiles.
Goal: Effectively analyze this data to detect and flag potential fraudulent behavior using at least 5 types of visualizations.

Business Objective

To analyze customer financial and behavioral data to:

Detect potential banking fraud

Assess credit risk effectively

Uncover hidden patterns and anomalies

Improve customer risk profiling

Strengthen lending decisions

Project Steps
1. Know Your Data

Import libraries (numpy, pandas, matplotlib, seaborn)

Load dataset

Check rows, columns, duplicates, null values

Initial inspection (head(), info(), describe())

2. Understanding Variables

Total columns: 28 (customer demographics, financial info, credit history, behavior)

Target variable: Credit_Score (Good, Standard, Poor)

Data types: float, int, object

Unique values checked for each column to identify categorical and continuous variables

3. Data Wrangling

Convert Age from float → integer

Drop rows with null values

Remove outliers in Annual_Income using IQR

Create new features:

Income_per_Account = Annual_Income / Num_Bank_Accounts

Credit_Score_Level to categorize credit score

4. KPIs (Key Performance Indicators)
Customer Demographics

Average Age: 33.32 years

Occupation distribution

Number of customers by income group

Financial Behavior

Average Annual Income: $50,505

Average Monthly In-hand Salary: $4,197

Average Debt-to-Income Ratio: 0.06

Average Credit Utilization Ratio: 32.29

Average Number of Bank Accounts: 5.37

Average Number of Credit Cards: 5.53

Loan & Credit Performance

Average Number of Loans per Customer: 3.53

Average Interest Rate: 14.53%

Total EMI as % of Income: 0.21%

Average Credit History Age: 221.22 years

Risk & Fraud Indicators

Average Number of Delayed Payments: 13.31

Delay from Due Date: min=0, max=25

Percent of Customers with Frequent Credit Inquiries: 92.81%

Percent of Customers with Changed Credit Limit: 100%

Credit Score Distribution: Standard=53,174, Poor=28,998, Good=17,828

Behavioral Insights

Payment Behavior distribution

Percent of customers who pay only minimum: 0%

5. Data Visualization & Storytelling

We used 18 charts to uncover patterns and insights:

Occupation-wise Number of Customers – Bar Chart

Age Distribution – Histogram

Annual Income by Occupation – Boxplot

Annual Income Distribution – Histogram

Monthly In-hand Salary vs Credit Score – Boxplot

Income Distribution by Credit Score – KDE Plot

Average Number of Loans vs Credit Score – Bar Chart

Types of Loans Availed – Stacked Bar Chart

Outstanding Debt vs Annual Income – Scatter Plot

Number of Delayed Payments vs Credit Score – Boxplot

Delay from Due Date Distribution – Histogram & KDE

Credit Utilization Ratio by Credit Score – Bar Chart
...and more

Insights Example:

Poor credit score customers tend to have higher debt and more delayed payments.

Income and monthly salary strongly correlate with credit score.

Certain occupations dominate customer base (Lawyers, Engineers).

Dataset Snapshot
Column	Description
Age	Customer age
Occupation	Profession
Annual_Income	Yearly income
Monthly_Inhand_Salary	Salary after deductions
Num_Bank_Accounts	Number of accounts held
Num_Credit_Card	Credit cards held
Credit_Utilization_Ratio	% of credit used
Outstanding_Debt	Total debt
Payment_Behaviour	Spending & repayment pattern
Credit_Score	Target variable (Good, Standard, Poor)
GitHub Repository

View Project on GitHub

Conclusion

This project provides a comprehensive understanding of customer financial behavior using real-world banking data. By leveraging EDA and visual storytelling, we:

Detect patterns of fraud

Identify risk factors affecting credit scores

Understand relationships between financial attributes

Impact:

Enhance fraud detection systems

Improve credit risk strategies

Optimize lending decisions

Strengthen customer profiling

This README can be directly used for GitHub to showcase your Paisabazaar Banking Fraud Analysis project professionally.
