# Retail--Data-cleaning-EDA-Python
# Retail Sales Data Analysis 🛍️

A comprehensive Python-based exploratory data analysis (EDA) and data cleaning pipeline for a retail sales dataset. This project uncovers key insights regarding customer demographics, product category performance, and sales revenue trends.



# 📊 Dataset Overview
The analysis is performed on a retail transaction dataset containing 1,000 records and 9 initial features
* Transaction ID: Unique identifier for each transaction.
* Date: The date the transaction took place.
* Customer ID: Unique identifier for the customer
* Gender: Gender of the customer
* Age: Age of the customer (ranging from 18 to 64 years)
* Product Category: The type of product purchased ( Beauty, Clothing, Electronics)
* Quantity: Number of units purchased per transaction 



# 🛠️ Data Cleaning & Validation
Before analysis, the dataset was cleaned and verified using Pandas:
* Missing Values: Checked and confirmed zero missing values across all columns
* Duplicates: Verified that there are no duplicate transaction rows
* Data Types: Converted the Date column from strings to standard datetime 
* Mathematical Integrity: Validated that Total Amount accurately equals Quantity * Price per Unit with zero calculation mismatches


#📈 Key Exploratory Data Analysis (EDA) Insights

#1. Product Category Performance
* Total Revenue: 
  * Electronics: $156,905 (342 transactions)
  * Clothing: $155,580 (351 transactions)
  * Beauty: $143,515 (307 transactions)
  

# 2. Customer Demographics & Sales by Gender
* Female Customers: Generated $232,840 in total revenue with an average spend of $456.55
* Male Customers: Generated $223,160 in total revenue with an average spend of $455.43
* Age Distribution: Customer ages span from 18 to 64 years, with a median age of 42 years



# 📊 Visualizations
revenue_by_category A  bar plot highlighting total revenue generated across different product categories
