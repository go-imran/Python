# Customer Lifetime Value (CLV) Analysis – Exploratory Data Analysis

## Project Overview
This project focuses on **Customer Lifetime Value (CLV)–oriented Exploratory Data Analysis (EDA)** using a large-scale online retail transaction dataset.  
The primary goal is to analyze **customer purchasing behavior, revenue contribution, order frequency, and retention-related patterns** to support data-driven business decisions.

The analysis converts raw invoice-level data into **customer-level insights** that can be leveraged for **marketing optimization, customer segmentation, and profitability analysis**.

---

##  Dataset Description
- **Dataset Type:** Online Retail Transaction Data  
- **Size:** 500,000+ rows  
- **Granularity:** Invoice-level transactions  
- **Key Columns:**
  - Customer ID
  - Invoice
  - Product / Category
  - Quantity
  - Revenue
  - Country
  - Invoice Type
  - Reason Category
  - Customer Type
  - Financial Impact
  - Invoice Date & Time

---

##  Tools & Technologies
- **Python**
- **Pandas & NumPy** – data manipulation and aggregation  
- **Matplotlib & Plotly** – exploratory and interactive visualizations  
- **Jupyter Notebook** – analysis and documentation  

---

##  Key Analysis Steps

###  Data Understanding & Preparation
- Loaded and validated large-scale transactional data
- Verified multiple invoices per customer
- Created customer-level aggregations:
  - Invoice count
  - Total quantity purchased
  - Total revenue
  - Recency (days since last purchase)
  - Monetary value

---

###  Customer Behavior & Segmentation
- Segmented customers based on:
  - Invoice frequency
  - Revenue contribution
  - Purchase quantity
  - Recency behavior
- Identified **high-frequency vs low-frequency customers**
- Analyzed **valid vs invalid sales** and customer types

---

###  Exploratory Data Analysis (EDA)
- **Country-level revenue analysis**
- **Product & category-level contribution analysis**
- **Invoice type and financial impact analysis**
- **Reason category analysis** to detect loss, damage, or operational issues
- **Time-based analysis** to understand purchasing patterns

---

###  CLV-Oriented Metrics Exploration
- Distribution of invoice frequency per customer
- Identification of top customers by:
  - Revenue
  - Number of invoices
- Monetary contribution analysis across segments
- Early-stage CLV behavior indicators

---

##  Key Insights
- A **small percentage of customers generate a large share of total revenue**
- High-frequency customers show:
  - Higher monetary value
  - Lower recency
- Certain product categories dominate overall revenue
- Returns, damages, and invalid transactions have **noticeable financial impact**
- Customer behavior varies significantly across regions and customer types

---

##  Business Value
This analysis enables businesses to:
- Identify and retain **high-value customers**
- Improve **targeted marketing and loyalty strategies**
- Detect **revenue leakage** from returns or invalid sales
- Prioritize **high-impact product categories**
- Build a strong foundation for **predictive CLV modeling**

---

##  Challenges & Learnings
- Efficient handling of **500k+ rows of transactional data**
- Designing meaningful customer-level features from invoice-level data
- Translating EDA outputs into **business-focused insights**
- Structuring analysis for scalability and future modeling

---

##  Future Work
- Build a **predictive CLV model** using RFM features
- Perform **cohort-based retention analysis**
- Apply **customer clustering** (K-Means / Hierarchical)
- Create **Power BI dashboards** for stakeholder reporting

---

##  Skills Demonstrated
- Real-world exploratory data analysis (EDA)
- Customer lifetime value concepts
- Feature engineering for customer analytics
- Business-oriented data storytelling
- Python-based analytical workflow

---

##  How to Use This Repository
1. Open the Jupyter Notebook (`.ipynb`) to view the analysis
2. Follow the step-by-step EDA workflow
3. Use insights as a base for CLV modeling or dashboard creation

---

##  Contact
**Md. Imran**  
Aspiring Business / Data Analyst  
📍 Bangladesh  

---

⭐ If you find this project useful, feel free to give it a star!
