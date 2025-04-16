# task-6
# 📊 Task 6: Sales Trend Analysis Using Aggregations

## 📝 Objective
Analyze **monthly revenue** and **order volume** from the `orders` table in the `online_sales` database using SQL aggregation functions.

---

## 🧰 Tools & Technologies
- **Database**: MySQL  
- **Tool**: MySQL Workbench (or any SQL IDE)

---

## 🗃️ Dataset
**Table:** `online_sales.orders`  
**Relevant Columns:**
- `order_id` – Unique identifier for each order
- `order_date` – Date of the order
- `amount` – Total revenue of the order
- `product_id` – Product reference (not used in this analysis)

---

## 📌 Requirements
- Extract month and year from `order_date`
- Calculate:
  - **Total Revenue** → `SUM(amount)`
  - **Order Volume** → `COUNT(DISTINCT order_id)`
