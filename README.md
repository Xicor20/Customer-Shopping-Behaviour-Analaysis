# 🛍️ Customer Shopping Behavior Analysis  

> **End-to-End Data Analytics Project | Python · MySQL · Power BI**

---

## 📌 Project Overview  

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  

The goal is to extract meaningful insights into customer behavior, identify revenue drivers, and support **data-driven decision-making** for marketing and product strategy.

---

## 🎯 Business Problem  

A retail company seeks to better understand changing customer purchasing patterns across demographics, products, and promotional strategies.

### Key Question:
> *How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize business performance?*

---

## 🧰 Tech Stack  

| Layer              | Tools Used |
|-------------------|------------|
| Data Processing    | Python (Pandas, NumPy) |
| Database           | MySQL |
| Data Analysis      | SQL |
| Data Visualization | Power BI |
| Version Control    | Git & GitHub |

---

## 📊 Dataset Summary  

- **Total Records:** 3,900  
- **Features:** 18  

### Key Attributes:
- **Demographics:** Age, Gender, Location, Subscription Status  
- **Transactions:** Item Purchased, Category, Purchase Amount, Season  
- **Behavioral Data:** Discounts, Purchase Frequency, Ratings, Shipping Type  

---

## 🔄 Project Workflow  

### 1. 🧹 Data Cleaning & Preparation (Python)
- Loaded and explored dataset using Pandas  
- Handled missing values (median imputation for review ratings)  
- Standardized column names (snake_case)  
- Feature engineering:
  - `age_group` (customer segmentation by age)
  - `purchase_frequency_days`  
- Removed redundant fields  
- Exported cleaned dataset to MySQL  

---

### 2. 🧮 Data Analysis (MySQL)
Performed structured business analysis using SQL queries:

- Revenue analysis by gender  
- Identification of high-spending discount users  
- Top-rated products analysis  
- Shipping type vs purchase behavior  
- Subscriber vs non-subscriber comparison  
- Discount dependency across products  
- Customer segmentation:
  - New  
  - Returning  
  - Loyal  
- Revenue contribution by age group  

---

### 3. 📈 Data Visualization (Power BI)
Built an interactive dashboard to present insights:

- Revenue distribution & KPIs  
- Customer segmentation breakdown  
- Product performance analysis  
- Purchase behavior trends  

---

## 🔍 Key Insights  

- 💰 **Male customers generated ~2x revenue** compared to female customers  
- ⭐ Top-rated products include Gloves, Sandals, and Boots  
- 📦 **Express shipping customers spend slightly more** than standard users  
- 👥 Majority of customers fall into the **Loyal segment**  
- 🎯 Heavy discount usage drives sales but may impact margins  
- 📊 Revenue contribution is relatively balanced across age groups  

---

## 💡 Business Recommendations  

- 🚀 **Increase Subscription Adoption**  
  Introduce exclusive benefits to boost conversions  

- 🎁 **Strengthen Loyalty Programs**  
  Incentivize repeat purchases to improve retention  

- ⚖️ **Optimize Discount Strategy**  
  Balance profitability with promotional effectiveness  

- 🛒 **Improve Product Positioning**  
  Promote high-rated and high-performing products  

- 🎯 **Enable Targeted Marketing**  
  Focus on high-value customer segments and behaviors  

---

📸 Dashboard Preview
