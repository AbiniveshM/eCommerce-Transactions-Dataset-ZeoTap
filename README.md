# eCommerce-Transactions-Dataset-ZeoTap
This repository contains the solution for the eCommerce Transactions dataset analysis and tasks, including exploratory data analysis (EDA), building a Lookalike Model, and performing customer segmentation through clustering techniques.

## Overview

This project analyzes an eCommerce dataset to derive valuable insights and predictions related to customers, transactions, and products. The analysis includes three primary tasks:

1. **Exploratory Data Analysis (EDA) and Business Insights**: Understand customer behaviors, trends, and insights.
2. **Lookalike Model**: Recommend similar customers based on their profiles and transaction history.
3. **Customer Segmentation / Clustering**: Segment customers using clustering algorithms to identify meaningful customer groups.

## Dataset Description

The project uses three datasets provided in CSV format:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Region where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Price of the product in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

## Tasks Overview

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Perform exploratory data analysis to understand the key trends and patterns.
- Derive actionable business insights.
- Insights are based on visualizations and key findings from the data.

### Task 2: Lookalike Model
- Build a recommendation system that suggests similar customers based on their profile and transaction history.
- The model takes user input and outputs the top 3 similar customers, along with their similarity scores.

### Task 3: Customer Segmentation / Clustering
- Perform customer segmentation using clustering techniques, considering both customer profiles and transaction data.
- Evaluate the clustering model using metrics such as the DB Index.
- Visualize the clusters for better interpretation.

## Requirements

- Python 3.7 or higher
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KMeans
- DBSCAN
- Jupyter Notebook
