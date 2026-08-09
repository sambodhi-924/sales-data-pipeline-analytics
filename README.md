# End-to-End Sales Data Pipeline & Analytics

An end-to-end data analytics project that processes raw sales data using **Python/Pandas**, stores the cleaned data in **MySQL**, performs business analysis using **SQL**, and presents insights through an interactive **Power BI dashboard**.

## Project Pipeline

**Raw CSV → Python/Pandas ETL → MySQL Database → SQL Analytics → Power BI**

## Technologies Used

* **Python** — Data cleaning and transformation
* **Pandas** — Data manipulation and validation
* **MySQL** — Data storage
* **SQL** — Business analysis
* **Power BI** — Interactive visualization

## Data Cleaning & Transformation

The raw dataset was intentionally prepared with real-world data quality issues and processed using Python/Pandas.

* Handled missing values
* Removed duplicate records
* Converted incorrect data types
* Validated and converted date fields
* Standardized categorical and text values
* Identified and handled extreme values
* Created derived fields such as:

  * Delivery Days
  * Profit Margin
  * Discount Category
  * Sales Category

## SQL Analysis

Performed business analysis using:

* Aggregations and `GROUP BY`
* Customer and product ranking
* Window functions
* Monthly sales trends
* Regional profitability
* Profit margin analysis
* Repeat customer analysis
* Discount impact on profit
* Top and loss-making products

## Power BI Dashboard

The interactive dashboard includes:

* Total Sales
* Total Profit
* Total Orders
* Profit Margin
* Sales Trend
* Sales by Category
* Sales vs Profit Analysis
* Sales & Profit by Sub-Category
* Profit by Discount
* Top 10 Loss-Making Products
* Category, Region, and Date filters

## Project Structure

```text
sales-data-pipeline-analytics/
│
├── data/
│   ├── raw_sales_data.csv
│   └── clean_sales_final.csv
│
├── python/
│   └── data_cleaning.ipynb
│
├── sql/
│   ├── database_setup.sql
│   └── analysis_queries.sql
│
├── powerbi/
│   └── sales_analytics_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

## Key Outcome

Built an end-to-end workflow that transforms raw, inconsistent sales data into a **clean analytical dataset, structured SQL database, and interactive business intelligence dashboard**.
