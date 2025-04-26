# Superstore Sales SQL Analysis

This project showcases SQL queries performed on a sample Superstore dataset to extract valuable business insights. The goal was to practice data wrangling, aggregation, and reporting skills using SQL, with a focus on real-world business use cases.

## Dataset
- **Source:** Kaggle's Superstore Sales dataset
- **Tables:** 1 (Superstore Orders)

## Tools Used
- Google Colab
- SQLite (via Python's sqlite3 library)
- Pandas

## Analysis Overview
The following queries were performed:

1. **Total Sales by Region:**  
   Summed sales across all regions to identify the most profitable areas.

2. **Top 10 Customers by Total Spend:**  
   Identified customers with the highest overall purchase amounts.

3. **Number of Orders by State:**  
   Counted the number of transactions per state to determine volume hotspots.

4. **Average Profit per Category:**  
   Calculated the average profitability of each product category.

5. **Monthly Sales Trend:**  
   Aggregated sales by month to analyze trends and seasonal impacts.

## Skills Demonstrated
- SQL aggregation functions (SUM, COUNT, AVG)
- GROUP BY, ORDER BY clauses
- Date-time formatting and extraction
- Data cleaning and preprocessing in Python
- Database creation and querying in Colab environment

## How to Run
- Upload the `Sample - Superstore.csv` file
- Load into a SQLite database via Pandas
- Execute SQL queries using `pd.read_sql_query()` in Colab

---

**Project by Rendi King**
