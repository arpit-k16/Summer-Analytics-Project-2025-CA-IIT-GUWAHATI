# StockSense: SQL-Based Inventory Optimization & Forecast Accuracy Analysis

StockSense is a data analytics project built as part of **Summer Analytics 2025 by Consulting & Analytics Club, IIT Guwahati**.

The project focuses on solving inventory management challenges for **Urban Retail Co.**, a mid-sized retail chain operating across physical stores, online platforms, and regional warehouses. The solution uses SQL-driven analytics, dashboard-ready datasets, and a machine learning model to identify stockouts, low inventory, overstocking, inventory turnover patterns, and demand forecast accuracy issues.

---

## Problem Statement

Urban Retail Co. manages more than 5,000 SKUs across categories such as groceries, home essentials, electronics, and personal care items. As operations expand across multiple cities and warehouses, the company faces inventory inefficiencies due to manual and reactive decision-making.

Key challenges include:

- Frequent stockouts of fast-moving products
- Overstocking of slow-moving items
- Poor visibility across stores, warehouses, regions, and categories
- Lack of real-time SKU performance tracking
- Inefficient reorder planning
- Underutilized sales, inventory, and warehouse data

---

## Project Objective

The objective of this project is to design a SQL-based inventory monitoring and optimization solution that converts raw retail data into actionable business insights.

This project helps answer questions such as:

- Which products are at risk of stockout?
- Which products are overstocked?
- What is the inventory turnover rate across stores and products?
- How accurate are demand forecasts?
- Which SKUs require better reorder planning?
- How can inventory decisions be improved using data?

---

## Tools & Technologies Used

- SQL
- Python
- Pandas
- XGBoost
- Streamlit
- Power BI
- Data Cleaning
- Data Visualization
- Inventory Analytics
- Demand Forecast Analysis

---

## Repository Structure

```bash
Summer-Analytics-Project-2025-CA-IIT-GUWAHATI/
│
├── Datasets/
│   ├── Inventory Snapshot.csv
│   ├── Forecast Deviation.csv
│   ├── Inventory Turnover Rate.csv
│   ├── Low Inventory.csv
│   └── Overstock.csv
│
├── SQL queries/
│   ├── Inventory Snapshot.sql
│   ├── Forecast Deviation.sql
│   ├── Inventory Turnover Rate.sql
│   ├── Low Inventory.sql
│   └── Overstockk.sql
│
├── dashboard/
│   ├── Forecast.csv
│   ├── Inventory Snapshot.csv
│   ├── Inventory Turnover Rate.csv
│   ├── Low Inventory.csv
│   └── Overstock.csv
│
├── ML MODEL/
│   ├── train.py
│   ├── predict.py
│   └── model files
│
├── requirements.txt
├── README.md
└── Summer Project 2025.pdf
```

---

## Dataset Overview

| Dataset | Description |
|---|---|
| Inventory Snapshot | Store-product level inventory, units sold, and units ordered data |
| Forecast Deviation | Comparison between actual demand and forecasted demand |
| Inventory Turnover Rate | Measures how efficiently inventory is sold and replaced |
| Low Inventory | Identifies products below required inventory levels |
| Overstock | Detects products with excess inventory compared to sales |

---

## SQL Analysis Performed

The SQL component forms the core of this project. Queries were written to extract, transform, and analyze retail inventory data.

Key SQL analyses include:

- Stock level calculation across stores and products
- Low inventory detection based on demand patterns
- Overstock identification using stock-to-sales ratio
- Inventory turnover rate calculation
- Forecast deviation analysis
- Stockout risk identification
- Store-product level inventory monitoring
- KPI summary generation for dashboarding

---

## Machine Learning Component

An additional machine learning model was developed to classify demand forecast accuracy.

The model predicts whether a forecast is:

- Accurate
- Underforecasted
- Overforecasted

### Model Used

- XGBoost Classifier

### Features Used

- Units sold
- Demand forecast
- Price
- Discount
- Promotion
- Weather condition
- Seasonality

This helps the business understand where demand forecasting is performing well and where improvements are required.

---

## Dashboard / Reporting

Dashboard-ready datasets were prepared for visual analysis in Power BI and Streamlit.

The dashboard/report focuses on:

- Inventory health monitoring
- Low-stock products
- Overstocked products
- Inventory turnover performance
- Forecast accuracy classification
- Product and store-level insights
- Business KPIs for decision-making

---

## Key Business KPIs

- Total Units Sold
- Current Inventory Level
- Units Ordered
- Stockout Risk
- Low Inventory Count
- Overstock Count
- Inventory Turnover Rate
- Forecast Deviation
- Forecast Accuracy Flag
- Stock-to-Sales Ratio

---

## Key Insights

- Fast-moving products can be identified using sales volume and inventory movement.
- Low inventory products require timely reorder planning to avoid stockouts.
- Overstocked products indicate excess capital locked in inventory.
- Inventory turnover helps measure how efficiently stock is being sold and replenished.
- Forecast deviation analysis highlights gaps between expected and actual demand.
- Forecast accuracy classification can support better future demand planning.

---

## Business Impact

The solution can help Urban Retail Co.:

- Reduce stockouts and missed sales
- Minimize overstocking and holding costs
- Improve reorder planning
- Increase visibility across stores and products
- Improve supplier and warehouse coordination
- Support data-backed inventory decisions
- Enhance customer satisfaction and profitability

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/arpit-k16/Summer-Analytics-Project-2025-CA-IIT-GUWAHATI.git
```

### 2. Navigate to the project folder

```bash
cd Summer-Analytics-Project-2025-CA-IIT-GUWAHATI
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

---

## Final Deliverables

This project includes:

- SQL scripts for inventory analysis
- Cleaned and processed datasets
- Dashboard-ready CSV files
- Machine learning model for forecast accuracy classification
- Streamlit-based deployment files
- Business insights and recommendations

---

## Program

This project was completed under:

**Summer Analytics 2025**  
**Consulting & Analytics Club, IIT Guwahati**

---

## Author

**Arpit Kumar**  
GitHub: arpit-k16

---

## Conclusion

StockSense demonstrates how SQL analytics, dashboarding, and machine learning can be combined to solve real-world inventory management problems. By transforming raw operational data into structured insights, the project supports smarter inventory decisions, better demand planning, and improved retail efficiency.
