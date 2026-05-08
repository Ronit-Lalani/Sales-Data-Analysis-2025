# 📊 Sales Dashboard 2025 — Excel Analytics Project

## 🚀 Project Overview

This project is an interactive Sales Dashboard built in Microsoft Excel to analyze sales performance, customer behavior, and operational KPIs using Pivot Tables, Pivot Charts, KPIs, and Slicers.

The dashboard provides insights into:

* Sales trends
* Category performance
* Channel performance
* Operational efficiency
* Customer metrics


# 🛠 Tools & Technologies Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* KPI Cards
* Custom Number Formatting
* Data Cleaning Techniques


# 📌 Dashboard KPIs

The dashboard tracks the following business metrics:

* Total Sales
* Total Orders
* Average Order Value (AOV)
* Delivery Rate
* Cancellation Rate
* Return Rate


# 📈 Dashboard Analysis

The dashboard includes:

* Sales by Category
* Sales by Channel
* Monthly Sales Trend
* Sales by Gender
* Sales by State
* AOV by Category


# 🎯 Key Features

✅ Interactive slicers for filtering
✅ Dynamic KPI reporting
✅ Business-focused operational metrics
✅ Custom number formatting (Lakhs/K format)
✅ Clean dashboard layout and visualization


# 🧹 Data Cleaning & Preparation

The raw dataset contained inconsistencies, missing values, formatting issues, and logical errors. The following data cleaning and preprocessing steps were performed to ensure accurate analysis and dashboard reporting:

## ✅ Data Cleaning Steps Performed

* Removed duplicate records based on Order ID
* Standardized categorical columns such as Gender, Status, and Channel
* Removed extra spaces using TRIM()
* Standardized text formatting using PROPER()
* Handled missing values in important fields
* Replaced blank categorical values with "Unknown"
* Cleaned inconsistent date formats (DMY and MDY)
* Converted all dates into a standard format
* Extracted Month from Date column for monthly analysis
* Identified and handled unrealistic values in Age column
* Removed invalid and inconsistent records
* Removed logically incorrect rows such as delivered orders with zero quantity
* Cleaned postal code column and handled invalid entries
* Converted Amount column from text format to numeric format
* Removed currency symbols and formatting issues from Amount column
* Handled negative values and inconsistent sales entries
* Corrected hidden spaces and formatting inconsistencies
* Refreshed Pivot Tables after cleaning
* Cleared Pivot cache to remove old/blank category references
* Applied custom number formatting for Lakhs (L) and Thousands (K)
* Structured KPIs dynamically using linked dashboard elements
* Connected slicers across all Pivot Tables for interactive filtering

## 📊 KPI Metrics Built

* Total Sales
* Total Orders
* Average Order Value (AOV)
* Delivery Rate
* Cancellation Rate
* Return Rate

## 🎯 Outcome

The cleaned dataset enabled accurate:

* KPI reporting
* Pivot analysis
* Interactive dashboard visualization
* Business performance insights


# 📷 Dashboard Preview

![Dashboard Preview](dashboard/sales-dashboard-preview.png)


# 📂 Project Structure

```text
Sales-Dashboard-2025/
│
├── data/
│   ├── store_sales_raw_data.xlsx
│   └── store_sales_cleaned_data.xlsx
│
├── dashboard/
│   └── sales-dashboard-preview.png
│
└── README.md


# 💡 Learning Outcomes

This project helped strengthen:

* Excel dashboard development
* Data visualization
* Business KPI analysis
* Interactive reporting
* Dashboard design principles


# 📌 Future Improvements

Possible future enhancements:

* Power BI version
* Advanced forecasting
* Customer segmentation
* Automated refresh using Power Query


# 👤 Author

Created by Ronit Lalani

Feel free to connect and share feedback.
