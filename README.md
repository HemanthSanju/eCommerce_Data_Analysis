# eCommerce_Data_Analysis

This repository contains the code and results of an analysis of an e-commerce transactions dataset. 

## Data Description

The dataset consists of three CSV files:

* `Customers.csv`: Contains customer information like ID, name, region, and signup date.
* `Products.csv`: Contains product information like ID, name, category, and price.
* `Transactions.csv`: Contains transaction information like ID, customer ID, product ID, transaction date, quantity purchased, and total value.

## Tasks

This project addresses three key tasks:

**1. Exploratory Data Analysis (EDA) and Business Insights:**

*   This script performs EDA on the dataset to understand customer behavior, product performance, and sales trends.
*   It generates a report with at least 5 actionable business insights derived from the analysis.

**2. Lookalike Model Development:**

*   This script builds a lookalike model that recommends similar customers based on a user's profile and transaction history.
*   The model considers both customer and product information and assigns similarity scores to recommended customers.
*   The output is a CSV file named `Lookalike.csv` containing a map of customer IDs to a list of similar customer IDs and their corresponding similarity scores.

**3. Customer Segmentation using Clustering:**

*   This script performs customer segmentation using a clustering algorithm.
*   It utilizes both customer profile and transaction information to group customers with similar characteristics.
*   The script calculates clustering metrics like the DB Index and visualizes the clusters using relevant plots.
*   A report details the number of clusters formed, DB Index value, and other relevant metrics.

## Deliverables

*   Jupyter Notebooks/Python scripts for each task.
*   PDF report with business insights from EDA.
*   `Lookalike.csv` file containing recommended similar customers and their similarity scores.
*   Report on customer segmentation results with visualizations.

## Getting Started

1.  Download the dataset:
       Customers.csv: https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing
       Products.csv: https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing
       Transactions.csv: https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing 
3.  Ensure you have Python and required libraries installed (pandas, scikit-learn, etc.).
4.  Run the Jupyter Notebooks or Python scripts for each task.

This project provides a framework for analyzing e-commerce customer data and deriving valuable insights for improved customer engagement and business strategies.
