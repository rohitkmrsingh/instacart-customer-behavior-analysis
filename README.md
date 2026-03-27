# Instacart Customer Behavior Analysis

## What this project is about

I worked on the Instacart dataset to understand how customers order groceries and what kind of products they tend to buy repeatedly.

The goal was to analyze real-world customer behavior and then present the insights using a clean and interactive Power BI dashboard.

---

## What I did

- Loaded and combined multiple datasets (orders, products, aisles, departments)
- Performed exploratory data analysis using Python (Pandas, Matplotlib, Seaborn)
- Analyzed:
  - when customers place orders
  - how frequently they return
  - which products and departments are most popular
  - reorder patterns
- Built a Power BI dashboard to present the findings in a simple and visual way

---

## Key things I found

- Around **59% of products are reordered**, which shows strong repeat behavior
- Most orders happen during the **daytime (late morning to afternoon)**
- Customers typically place orders every **~11 days**
- **Produce** is the most ordered category
- **Dairy & Eggs** has one of the highest reorder rates
- **Bananas** are the most frequently purchased item

---

## Dashboard

The Power BI dashboard includes:

- Total orders, total products ordered, and reorder rate
- Orders by hour and day
- Top 10 products
- Department-wise analysis
- Reorder rate by department
- A filter to explore data by department

---

## Dashboard Preview

![Dashboard](image/image/Screenshot 2026-03-26 230345.png)

---

## Files in this repo

- `notebook/instacart_eda.ipynb` → EDA done in Python
- `dashboard/instacart_dashboard.pbix` → Power BI dashboard
- `image/image/Screenshot 2026-03-26 230345.png` → dashboard screenshot

---

## Why this project matters

This kind of analysis can help businesses:
- understand customer buying patterns
- improve recommendations
- plan inventory better
- increase customer retention