# E-Commerce Customer Lookalike and Clustering Analysis

This project involves the analysis of an eCommerce dataset with the aim of providing business insights, building a lookalike model, and performing customer segmentation.

## Project Overview

The dataset consists of three files:
1. **Customers.csv**: Contains customer profile data (CustomerID, Name, Region, SignupDate).
2. **Products.csv**: Contains product details (ProductID, Name, Category, Price).
3. **Transactions.csv**: Contains transaction data (TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue).

## Key Tasks

### 1. **Exploratory Data Analysis (EDA)**
   - Cleaned and processed the data.
   - Performed analysis to derive business insights such as high-value customers, product preferences, and purchasing behavior patterns.

### 2. **Lookalike Model**
   - Built a lookalike model to recommend similar customers based on purchasing behavior.
   - The model uses customer and product information to identify the top 3 similar customers for each of the first 20 customers.

### 3. **Customer Segmentation**
   - Applied clustering algorithms to segment customers based on profile and transaction data.
   - Evaluated clusters using the DB Index and visualized the customer segments.

## Files

- **Ansh_Porwal_EDA.ipynb**: Jupyter Notebook for Exploratory Data Analysis (EDA).
- **Ansh_Porwal_Lookalike.ipynb**: Jupyter Notebook for Lookalike Model.
- **Ansh_Porwal_Lookalike.csv**: Output CSV file containing lookalike recommendations.
- **Ansh_Porwal_Clustering.ipynb**: Jupyter Notebook for Customer Segmentation/Clustering.
- **Ansh_Porwal_Clustering.pdf**: Report with clustering results and insights.
- **Ansh_Porwal_EDA.pdf**: Report with business insights from the EDA.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter


