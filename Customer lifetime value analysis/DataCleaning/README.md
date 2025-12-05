 Customer Lifetime Value (CLV) Analysis – Feature Engineering Completed

This part of the project focuses on cleaning the Online Retail dataset and creating all the CLV-ready derived variables using Python (Pandas).
These engineered columns will be used later for RFM, CLV modeling, segmentation, and predictive analytics.

 1. Completed Data Cleaning Steps

Handled NULLs and invalid entries

Standardized invoice types (Sale / Return / Manual)

Cleaned descriptions, quantity issues, duplicate invoices

Converted dtypes and fixed negative quantity inconsistencies

 2. Feature Engineering Summary

The following columns were created through rule-based classification + business logic:

🧾 Sales & Invoice Logic

Invoice_Type → Sale / Return / Check / Manual

Is_Positive_Quantity

Is_Valid_Sale

Revenue (only for valid sales)

Non-Sale Classification

Reason_Category → Return, Sample, Damage, E-commerce Issue, Credit, Manual Fee, etc.

Lost_Quantity

Non_Sale_Quantity

Financial_Impact (non-sale monetary loss)

Customer-Level Metrics

Customer_Type

Customer_Invoice_Count

Customer_Quantity_Sum

Customer_Revenue_Sum

CLV Metrics

Recency_Days

Monetary_Value

Avg_Order_Value

All these columns prepare the dataset for RFM Analysis + CLV Modeling.

3. Upcoming Tasks

RFM Segmentation

Machine Learning Model for CLV Prediction

Customer Segmentation using KMeans
