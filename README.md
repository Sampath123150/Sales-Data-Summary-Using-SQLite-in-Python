# Sales-Data-Summary-Using-SQLite-in-Python
A beginner-friendly project that creates a tiny SQLite database, runs SQL queries in Python, and visualizes sales revenue using Matplotlib. Perfect for learning database integration, data analysis, and simple charting in Jupyter Notebook.

---

## 📦 Tools & Technologies

- **Python**
- **SQLite3** (built-in — no installation required)
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🎯 Objective

- Create a tiny SQLite database.
- Insert sample sales data.
- Run SQL queries inside Python.
- Display results using print statements.
- Visualize revenue using a simple Matplotlib bar chart.

---

## 🗂️ Dataset Description

The project uses a single table: **sales**

| Column    | Type    | Description              |
|-----------|---------|--------------------------|
| product   | TEXT    | Product name             |
| quantity  | INTEGER | Units sold               |
| price     | REAL    | Price per unit (in INR)  |

Sample inserted data:

| product  | quantity | price |
|----------|----------|--------|
| Laptop   | 2        | 45000 |
| Mouse    | 5        | 500   |
| Keyboard | 3        | 800   |

---

## 📁 Project Structure

### What the Project Does

Creates a SQLite database file named sales_data.db

Inserts sample sales records

Retrieves total quantity and revenue per product using SQL

Displays the result in a table format

Plots a bar chart to show revenue by product

### Output Summary

The console displays total quantity and revenue for each product.
A bar chart visualizing revenue appears inside the Jupyter Notebook.

### Future Enhancements

Add date-based analysis

Create more tables and relationships

Build a dashboard using Streamlit

Export results to CSV or Excel

