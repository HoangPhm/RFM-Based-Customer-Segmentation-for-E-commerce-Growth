# RFM-Based-Customer-Segmentation-for-E-commerce-Growth
This project uses the 'Online Retail' dataset to perform RFM-based Customer Segmentation. We aim to identify distinct customer groups (Loyal, At-Risk, New) based on Recency, Frequency, and Monetary value. The goal is to inform personalized marketing strategies to maximize customer lifetime value (CLV) and optimize retention efforts.

**Tools Used:** Python

# Table of Contents

[📌 1. Background & Overview](#background--overview)  
[📂 2. Dataset Description & Data Structure](#dataset-description--data-structure)  
[🧹 3. Data Cleaning & Preprocessing](#data-cleaning--preprocessing)  
[🔍 4. Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
[🧮 5. Apply RFM Model](#apply-rfm-model)  
[📊 6. Visualization & Analysis](#visualization--analysis)  
[💡 7. Insight & Recommendation](#insight--recommendation)

# 1. 📌 Background & Overview
## Project Objective ##
**Context**
- The e-commerce company behind the "Online Retail" dataset needs to move beyond a "one-size-fits-all" marketing strategy to survive and grow in a competitive market. Given the large volume of transactional data, manual customer classification is inefficient.
- The primary object is to utilize the RFM (Recency, Frequency, Monetary) model to classify the customer base into distinct, actionable segments like Champions and At-Risk groups.
- This project involves data preparation, RFM score calculation, segmentation, and visualization, leading to actionable recommendations for the Marketing and Sales teams to optimize their customer strategies.

**👤 Target Audience**
- Marketing & Sales Department
- Decision-makers & Stakeholders

**❓ Business Questions:**

✔️ Customer Identification: What are the distinct customer segments inherent in the transaction data (e.g., Champions vs. Hibernating)? 

✔️ Revenue Concentration: Which customer groups contribute the most to revenue, and do they follow the Pareto Principle (80/20 rule)? 

✔️ Churn Risk: Which customers are at the highest risk of leaving (churning) and require immediate retention efforts? 

✔️ Strategy Optimization: How can we tailor marketing strategies for each segment to maximize Customer Lifetime Value (CLV) and engagement?

**ℹ️ RFM Analysis Overview**

RFM is a marketing analysis technique used to evaluate the value of a customer based on their purchasing history. It groups customers based on three key metrics:

🕒 Recency (R): How recently did the customer make a purchase? (A shorter duration is better).

🔄 Frequency (F): How often do they purchase? (Higher is better).

💰 Monetary Value (M): How much do they spend? (Higher is better).

**Why RFM?** It is based on the Pareto Principle (80/20 Rule), assuming that 80% of revenue comes from 20% of customers. RFM helps identify that top 20% (High Value) and differentiates them from low-value or lost customers.

# 2. 📂 Dataset Description & Data Structure
