# 🛍️ Sales Analysis of Electronics Store

## 📄 Project Overview
This project analyzes 12 months of sales data from an electronics store to answer key business questions and uncover actionable insights. The dataset contains hundreds of thousands of purchase records, including details such as month, product type, cost, and purchase address.

We used **Python Pandas** for data manipulation and **Matplotlib** for data visualization to explore and answer critical business questions.

---

## 🧹 Data Cleaning
Before starting the analysis, the dataset was cleaned by performing the following steps:
- Dropped `NaN` values from the DataFrame.
- Removed rows based on specific conditions.
- Converted columns to appropriate data types (e.g., `to_numeric`, `to_datetime`).

---

## ❓ Business Questions Explored
The analysis was structured around answering the following high-level business questions:
1. **What was the best month for sales?**  
   - How much revenue was earned that month?
2. **Which city sold the most products?**
3. **What time should we display advertisements to maximize sales?**
4. **What products are most often sold together?**
5. **What product sold the most, and why?**

---

## 🛠️ Techniques Used
To answer these questions, the following methods and techniques were utilized:
- **Data Manipulation**:
  - Concatenating multiple CSV files into a single DataFrame using `pd.concat`.
  - Adding new columns by parsing existing data.
  - Applying custom logic with `.apply()` and performing aggregate analysis with `.groupby()`.
- **Data Visualization**:
  - Creating bar charts and line graphs to visualize sales trends.
  - Styling and labeling graphs for better readability.

---

## 📊 Key Insights
- **The best month for sales** was **December**, with total sales of **$4,613,443.34 USD**.
- **San Francisco, CA**, sold the most products among all cities.
- **Peak advertisement times** were identified as slightly before **11 AM** and **7 PM**, maximizing customer engagement.
- **Frequently purchased product combinations**:
  - iPhone & Lightning Charging Cable → **1,005 times**
  - Google Phone & USB-C Charging Cable → **987 times**
- The **most sold products**, AAA and AA batteries, were highly popular due to their **affordable cheap prices** compared to other items.
