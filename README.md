# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.


## 📌 Project Overview
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence.


## 🔄 Project Workflow
✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.

![Project Workflow](https://github.com/user-attachments/assets/8bbd5dc9-eb6c-40c1-8f19-c08b4107f654)


## 🛠️ Tech Stack & Tools
* **Data Processing & Cleaning:** Python (Pandas)
* **Database & Querying:** PostgreSQL
* **Data Visualization:** Power BI Desktop
* **Version Control:** Git, GitHub

---

## 📊 Dataset Summary
* **Total Transactions:** 3,900 rows
* **Total Attributes:** 18 columns
* **Key Demographic Features:** Age, Gender, Location, Subscription Status
* **Purchasing Attributes:** Item Purchased, Category, Purchase Amount (USD), Season, Size, Color
* **Behavioral Metrics:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
* **Data Quality Note:** 37 missing values identified in the `Review Rating` column.

---
### 📊 Structured Data Analysis (SQL)
Key business questions answered via PostgreSQL queries:

1. **Revenue by Gender:**
   * **Male:** $157,890 total revenue
   * **Female:** $75,191 total revenue
2. **Top-Rated Products:** Gloves (3.86 avg rating) and Sandals (3.84 avg rating) lead product satisfaction.
3. **Shipping Type Impact:** Express shipping users average slightly higher spend ($60.48) compared to Standard shipping ($58.46).
4. **Subscription Analysis:**
   * Non-Subscribers account for **73%** of customers ($170,436 revenue).
   * Subscribers account for **27%** of customers ($62,645 revenue).
   * Average spend per order is nearly identical ($59.49 for Subscribers vs. $59.87 for Non-subscribers).
5. **Discount Dependency:** Hats (50%), Sneakers (49%), and Coats (49%) have the highest proportions of discounted purchases.
6. **Customer Segmentation:** Classified users into **Loyal** (3,116), **Returning** (701), and **New** (83) segments based on purchase history.
7. **Top Category Sellers:**
   * *Clothing:* Blouse & Pants (171 orders each)
   * *Accessories:* Jewelry (171 orders)
   * *Outerwear:* Jacket (163 orders)
   * *Footwear:* Sandals (160 orders)
8. **Revenue by Age Group:** Young Adults generated the highest overall revenue ($62,143), followed closely by Middle-Aged customers ($59,197).

---

## 📈 Interactive Power BI Dashboard
An interactive Power BI dashboard was built to visualize core KPIs and behavioral trends:

### Key Dashboard Highlights:
* **KPI Header Cards:** Total Customers (3.9K), Average Purchase Amount ($59.76), Average Review Rating (3.75).
* **Subscription Breakdown:** Visualized customer distribution between subscribed (27%) and non-subscribed (73%) shoppers.
* **Category Performance:** Highlighting **Clothing** as the top revenue and sales driver, followed by **Accessories**, **Footwear**, and **Outerwear**.
* **Demographic Breakdown:** Revenue and order volume sliced across age brackets and gender demographics.
* **Dynamic Slicers:** Interactive filtering by Subscription Status, Gender, Category, and Shipping Method.

<img width="878" height="492" alt="dashboard" src="https://github.com/user-attachments/assets/74bde77c-12a3-4aab-8f53-5b7ef53c8b1a" />

---

## 💡 Key Business Recommendations
* **Boost Subscription Adoption:** Introduce exclusive subscriber perks (e.g., free shipping, early access) to convert the 73% non-subscriber base.
* **Optimize Discount Strategies:** Re-evaluate promotional margins on high-discount items like Hats and Sneakers to prevent margin erosion.
* **Target High-Value Segments:** Tailor marketing campaigns toward **Young Adults** and **Middle-aged** demographics who generate the highest overall revenue volume.
* **Leverage Top Performers:** Highlight highly rated items (Gloves, Sandals, Boots) in promotional materials and cross-selling campaigns.

  


## 📜 License

This project is licensed under the MIT License — feel free to fork, customize, or use it as a reference for portfolio development.

## 👩‍💻 Author

Sai Sahithi
Data Analyst | SQL | Python | Power BI | PostgreSQL | Excel

⭐ If you find this project useful, feel free to explore the SQL scripts, Power BI dashboard, and documentation.
