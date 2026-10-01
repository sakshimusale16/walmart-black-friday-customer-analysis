# walmart-black-friday-customer-analysis
Exploratory data analysis and statistical inference on Walmart Black Friday customer purchase behavior using Python.
# Walmart Black Friday Customer Purchase Analysis

## Overview

This project analyzes Walmart's Black Friday customer purchase data to understand how customer demographics and behavioral factors influence purchasing patterns.

The analysis focuses on differences in purchase behavior across gender, age groups, marital status, city categories, and product categories.

## Business Problem

Walmart wants to understand customer purchase behavior during Black Friday, particularly whether spending patterns differ between male and female customers and across other demographic groups.

## Dataset

The dataset contains approximately 550,000 transactions with information including:

- User ID
- Product ID
- Gender
- Age
- Occupation
- City Category
- Years in Current City
- Marital Status
- Product Category
- Purchase Amount

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab

## Analysis Performed

- Data exploration and cleaning
- Data type optimization
- Missing value analysis
- Outlier detection using IQR
- Exploratory Data Analysis (EDA)
- Customer segmentation by demographics
- Gender-based purchase analysis
- Age-based purchase analysis
- Marital status analysis
- Product category analysis
- Bootstrapping
- Confidence interval estimation
- Central Limit Theorem analysis

## Key Insights

- Male customers account for the majority of transactions in the dataset.
- Customers aged 26–35 contribute the highest number of purchases.
- Customers aged 51–55 show the highest average purchase amount.
- City Category B contributes the largest number of transactions.
- Male and female customers show differences in average purchase behavior.
- Increasing sample size produces narrower confidence intervals and more stable estimates.

## Statistical Analysis

Bootstrapping was used to estimate sampling distributions and confidence intervals for different customer groups.

Sample sizes of 300, 3,000, 30,000, and the full dataset were compared to demonstrate the effect of sample size on confidence interval width and sampling distributions.

The analysis demonstrates the Central Limit Theorem and shows how larger samples provide more precise estimates of population parameters.


