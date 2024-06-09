##
Time-Series-Analysis

## Group Members

* Ben madani Yazid
* Mohammed Sameer

# Predict Future Sales

## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset consists of transactions made by European cardholders in September 2013. With the prevalence of credit card fraud, it is crucial for financial institutions to identify and prevent fraudulent activities to protect customers and minimize losses.
you can find the dataset [Here](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales).

## Dataset Description
The dataset appears to contain sales data with the following columns:

date: The date of the transaction.
date_block_num: A numerical representation of the month of the transaction (e.g., 0 for January 2013).
shop_id: An identifier for the shop where the transaction occurred.
item_id: An identifier for the item being sold.
item_price: The price of the item.
item_cnt_day: The number of items sold that day (can be negative if an item was returned).
The dataset is highly unbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions.

## Anomaly Detection

 outliers, novelties, or exceptions ... detect by 
 * Statistical Methods: Use statistical measures such as mean, standard deviation, z-scores, or percentiles 
 * Domain-Specific Approaches
### Recommended Evaluation Metric


### Getting Started

### Prerequisites
install requirements.txt file
pip install -r requirements. txt
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
### References