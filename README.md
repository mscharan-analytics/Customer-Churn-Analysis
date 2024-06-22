# QWE Case Study on Customer Churn Analysis

## Project Overview

This project analyzes customer churn for company QWE using a logistic regression model. The goal is to predict customer churn probabilities and identify the key factors contributing to churn.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Loading and Exploration](#data-loading-and-exploration)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Model Implementation](#model-implementation)
5. [Analysis of Specific Customers](#analysis-of-specific-customers)
6. [Top 100 Customers at Risk of Churn](#top-100-customers-at-risk-of-churn)
7. [Conclusion](#conclusion)

## Introduction

The project uses various Python libraries including pandas, scikit-learn, matplotlib, and seaborn to analyze customer data and build a predictive model for churn.

## Data Loading and Exploration

- Data is loaded from an Excel file 'UV6696-XLS-ENG.xlsx'
- Initial data exploration is performed to understand the structure and content of the dataset

## Exploratory Data Analysis

- Visualizations are created to understand the distribution of various features
- The relationship between customer age and churn rate is examined

## Model Implementation

- A logistic regression model is implemented using scikit-learn
- The model is evaluated using metrics such as accuracy, confusion matrix, and ROC curve

## Analysis of Specific Customers

- Churn probabilities are predicted for specific customers (IDs 672, 354, 5203)
- The top contributing factors for these customers' churn probabilities are identified

## Top 100 Customers at Risk of Churn

- The model predicts churn probabilities for all customers
- The top 100 customers with the highest churn probabilities are identified
- The top three drivers of churn for each of these customers are determined

## Conclusion

The project provides insights into customer churn patterns and identifies key factors contributing to churn. This information can be used by QWE to develop targeted retention strategies.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- numpy

## Usage

1. Ensure all required libraries are installed
2. Load the data from 'UV6696-XLS-ENG.xlsx'
3. Run the Jupyter notebook or Python script to perform the analysis

## Output

The results, including the list of top 100 customers at risk of churn and their top three churn drivers, are exported to 'churn_results.xlsx'.
