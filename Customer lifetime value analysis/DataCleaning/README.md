# Customer Lifetime Value (CLV) Analysis – Feature Engineering

This part of the project focuses on **cleaning the Online Retail dataset** and creating all the **CLV-ready features** using Python (Pandas). These features will later be used for **RFM analysis, CLV modeling, customer segmentation, and predictive analytics**.

---

## **Completed Data Cleaning Steps**

We performed the following cleaning tasks to make the dataset ready for analysis:

- Handled **NULLs and invalid entries**.  
- Standardized **invoice types** (Sale / Return / Manual).  
- Cleaned **product descriptions**, fixed **quantity issues**, and removed **duplicate invoices**.  
- Converted **data types** and corrected **negative quantity inconsistencies**.  

---

## **Feature Engineering Summary**

We created new columns using **business rules** and **logic** to make the dataset CLV-ready.

### **1. Sales & Invoice Logic**
- **Invoice_Type** → Classified as Sale / Return / Check / Manual.  
- **Is_Positive_Quantity** → Indicates if quantity is positive.  
- **Is_Valid_Sale** → Marks valid sales only.  
- **Revenue** → Calculated only for valid sales.  

### **2. Non-Sale Classification**
- **Reason_Category** → Categorized as Return, Sample, Damage, E-commerce Issue, Credit, Manual Fee, etc.  
- **Lost_Quantity** → Quantity lost due to returns, damage, etc.  
- **Non_Sale_Quantity** → Total non-sale quantity.  
- **Financial_Impact** → Monetary loss from non-sale items.  

### **3. Customer-Level Metrics**
- **Customer_Type** → Categorize customers based on activity.  
- **Customer_Invoice_Count** → Number of invoices per customer.  
- **Customer_Quantity_Sum** → Total quantity purchased.  
- **Customer_Revenue_Sum** → Total revenue per customer.  

### **4. CLV Metrics**
- **Recency_Days** → Days since last purchase.  
- **Monetary_Value** → Total revenue per customer.  
- **Avg_Order_Value** → Average order value per customer.  

These columns **prepare the dataset for RFM analysis and CLV modeling**.

---

## **Upcoming Tasks**

The next steps in the project include:

- **RFM Segmentation** → Classify customers based on Recency, Frequency, and Monetary value.  
- **Machine Learning Model for CLV Prediction** → Predict future customer lifetime value.  
- **Customer Segmentation using KMeans** → Group similar customers for targeted strategies.
