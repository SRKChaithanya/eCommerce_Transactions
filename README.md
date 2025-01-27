# eCommerce Transactions Analysis

## Description
This project involves analyzing an eCommerce transactions dataset to derive actionable insights, build predictive models, and perform customer segmentation. The analysis is structured into three main modules: Exploratory Data Analysis (EDA), Lookalike Model, and Customer Segmentation.

## Modules Overview

### 1. Exploratory Data Analysis (EDA)
The EDA module provides a comprehensive analysis of the dataset, including:
- Distribution of customers by region.
- Average transaction value per region.
- Monthly transaction trends.
- Top products by sales volume.
- Customer purchase frequency distribution.

Insights derived from the EDA help in understanding customer behavior and identifying market opportunities.

### 2. Lookalike Model
The Lookalike Model recommends similar customers based on their profiles and transaction history. It utilizes:
- Customer demographics and transaction data.
- Cosine similarity to identify top lookalikes.

The output is a CSV file containing the top similar customers for each of the first 20 customers in the dataset.

### 3. Customer Segmentation
This module performs customer segmentation using clustering techniques. Key features include:
- K-Means clustering to group customers based on their transaction behavior.
- Calculation of clustering metrics such as the Davies-Bouldin Index and silhouette score.
- Visualization of customer segments to identify distinct groups.

## Installation Instructions
To run this project, ensure you have Python installed along with the necessary libraries:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

