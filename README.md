# SQLite-Database-using-Python-Elevate-lab-Task-5


## 📊 Sales Summary Project with SQLite & Python

### 🔍 Objective

To create a simple sales summary using Python and SQLite by:

* Running SQL queries to analyze sales data
* Filtering sales by region or date
* Creating monthly revenue trends
* Visualizing data using matplotlib
* Exporting results to CSV

---

### 🛠️ Tools & Libraries

* **Python 3**
* **SQLite** (built-in with Python)
* **pandas**
* **matplotlib**

---

### 📁 Project Structure

```
sales_summary_project/
├── sales_data.db               # SQLite database file
├── sales_analysis.py          # Main Python script (or .ipynb)
├── region_sales_summary.csv   # Region-wise summary (auto-generated)
├── monthly_revenue_trend.csv  # Monthly trend data (auto-generated)
├── sales_chart.png            # Revenue bar chart (optional)
└── README.md                  # Project documentation
```

---

### 📋 Features

✅ Create and populate SQLite database
✅ Run SQL queries for summary by product
✅ Filter data by region (North, South, East, West)
✅ Analyze monthly revenue trends
✅ Export results to CSV
✅ Visualize with bar and line charts

---

### 🚀 How to Run

1. **Install dependencies** (if not already available):

   ```bash
   pip install pandas matplotlib
   ```

2. **Run the script** (choose one):

   * As a `.py` file:

     ```bash
     python sales_analysis.py
     ```
   * Or open and run cells in `sales_analysis.ipynb` (Jupyter Notebook)

3. **Output**:

   * Printed summary tables
   * Charts displayed with matplotlib
   * CSV files generated:

     * `region_sales_summary.csv`
     * `monthly_revenue_trend.csv`

---

### 📈 Example Output

**Region Sales Summary (North):**

| Product | Total Qty | Revenue |
| ------- | --------- | ------- |
| Apple   | 10        | 15.00   |
| Banana  | 20        | 10.00   |
| Orange  | 10        | 8.00    |

**Monthly Revenue Trend:**

| Month   | Total Revenue |
| ------- | ------------- |
| 2025-06 | 132.50        |

---

### 🧠 What You Learn

* How to integrate SQL into Python with SQLite
* Basic SQL aggregations (SUM, GROUP BY)
* Plotting with matplotlib
* Saving DataFrames to CSV
* Real-world sales trend analysis techniques

---


