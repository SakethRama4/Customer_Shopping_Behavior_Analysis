# 🛍️ Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using real transactional data from **3,900 purchases** across multiple product categories.  
The goal is to uncover **spending patterns**, **customer segments**, **product preferences**, and **subscription behaviors** to help businesses make data-driven strategic decisions.

## 📊 Dataset
- **Total Records:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - **Demographics:** Age, Gender, Location, Subscription Status  
  - **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
  - **Behavioral Indicators:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type  
- **Missing Data:** 37 missing values in `review_rating` column (handled using median imputation per product category).

## 🧰 Tools & Technologies
- **Python** (Data Cleaning & Feature Engineering)  
- **MySQL** (Data Analysis with SQL Queries)  
- **Power BI** (Interactive Dashboard & Visualization)  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** (EDA & Visualization)

## 🪜 Steps & Methodology

### 1. Data Cleaning & Preparation (Python)
- Loaded data using `pandas`
- Explored structure with `info()` and summary statistics with `describe()`
- Handled missing values in `review_rating` column (median imputation)
- Standardized column names to `snake_case`
- Engineered new features:
  - `age_group` (binned age categories)
  - `purchase_frequency_days` (derived from purchase timestamps)
- Checked for redundant columns and removed `promo_code_used`
- Integrated cleaned dataset into MySQL database

### 2. SQL Analysis
Answered key business questions, including:
- Revenue comparison by gender  
- High-spending discount users  
- Top 5 products by rating  
- Standard vs. Express shipping spend  
- Subscribers vs. non-subscribers  
- Discount-dependent products  
- Customer segmentation (New, Returning, Loyal)  
- Top 3 products per category  
- Repeat buyers and subscription patterns  
- Revenue contribution by age group

### 3. Dashboard (Power BI)
- Designed a **fully interactive Power BI dashboard** to visualize:
  - Revenue trends and segmentation
  - Product performance
  - Subscription and shipping behavior
  - Customer loyalty insights

## 📈 Results & Insights
- **High-spending segments** identified among express shipping users and subscribers  
- **Top-rated products** aligned closely with best-sellers  
- **Discount usage patterns** highlighted potential margin optimization areas  
- **Age group targeting** revealed key revenue contributors  
- Loyalty and subscription behaviors provided actionable marketing insights.

---

## 🧑‍💻 Author
**Saketh Rama** – Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/saketh-rama/) | 📧 [Email](mailto:ramasaketh4@gmail.com)


---

✅ *This project demonstrates end-to-end data analysis — from raw data cleaning to insight visualization.*

