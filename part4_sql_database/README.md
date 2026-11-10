# TrendPulse Part 4: SQL Database Querying & Relational Analysis

This module transitions the TrendPulse project from Pandas dataframes to a relational SQL database structure using SQLite. It enables complex multi-table querying, filtering, and cross-market aggregation of YouTube trending video statistics.

## 📂 Module Contents

* **`TrendPulse_Part4.ipynb`**: The primary Jupyter Notebook handling SQLite database initialization, CSV data ingestion, and advanced SQL analytical queries.
* **`trendpulse.db`**: The local SQLite database file containing structured tables for US, GB, IN datasets and category lookups.

---

## 🔍 Key SQL Analysis Areas

1. **Table Ingestion & Normalization:** Storing multi-region datasets and category mappings into structured relational tables.
2. **Aggregations & Grouping:** Calculating average views, likes, and engagement scores grouped by category name and region using `JOIN` operations.
3. **Complex Filtering:** Extracting viral video trends, ranking top creators, and sorting metrics dynamically using SQL clauses (`WHERE`, `GROUP BY`, `ORDER BY`, `LIMIT`).

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Ensure your cleaned CSV datasets are accessible in your workspace path.
3. Run the cells sequentially to build the database, execute SQL queries, and analyze results.
