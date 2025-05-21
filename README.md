# 📊 Amazon Retail Performance Dashboard

This project explores and visualizes Amazon retail sales data to evaluate product profitability, regional performance, shipping efficiency, and sales trends from January 2011 to December 2014. It includes data cleaning in Excel and dashboard development in Tableau.

---

## 🔍 Project Overview

Using the [Amazon Sales Dataset from Kaggle](https://www.kaggle.com/datasets/anandshaw2001/amazon-sales-dataset/data), this analysis provides insights into:

- Product-level profitability and profit margin
- Sales and revenue trends over time
- Regional performance across U.S. states
- Shipping duration trends
- Category-level sales performance

The final output is an interactive Tableau dashboard that allows for exploratory analysis and business insight discovery.

---

## 🛠️ Tools & Techniques

- **Excel**:  
  - Cleaned and transformed raw data  
  - Split combined location fields into `Country`, `City`, `State`  
  - Added calculated fields like `Profit_Margin`, `Category`, `Product Name`  
  - Standardized the `Date` column format  

- **Tableau**:  
  - Developed an interactive dashboard with:
    - Dual-axis charts for total orders and revenue over time
    - Product profitability report
    - Geographic sales performance map
    - Category-level sales donut chart
    - Shipping duration bar chart by state

---

## 📈 Key Insights

- **Chairs** had the highest revenue ($101,781.36) but a low profit margin (2.13%).
- **Tables, machines, and appliances** had **negative profit margins**, indicating potential discontinuation or price adjustments.
- **California and Washington** generated the most revenue and profit.
- **Wyoming** had the highest average shipping duration (flagged blue for >4 days).
- Revenue and orders **steadily increased** from 2011 to 2014.

---

## 📎 Tableau Dashboard

🔗 [View the Tableau Dashboard Here](PASTE_YOUR_TABLEAU_LINK_HERE)

---

## 📌 Next Steps

- Add interactivity with category/year filters
- Automate data cleaning with Python or Alteryx
- Integrate customer-level or cohort analysis if data permits

---

## 🧠 Author

**Alessandra Bielli**  
Data Analyst | Marketing Scientist  
📍 Philadelphia, PA  


