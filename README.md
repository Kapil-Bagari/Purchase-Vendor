# Purchase & Vendor MIS Dashboard

## 📌 Project Overview

The Purchase & Vendor MIS Dashboard is an Excel-based Management Information System (MIS) project designed to monitor and analyze purchasing activities, vendor performance, payment status, delivery performance, and spending patterns.

This project simulates a real-world MIS reporting workflow, starting with raw and inconsistent purchase data and transforming it into a clean, structured dataset and an interactive management dashboard.

---

## 🎯 Business Objective

The main objective of this project is to provide management with a clear view of:

- Overall purchasing activity
- Vendor-wise purchase performance
- Pending vendor payments
- Delivery performance
- Delayed purchase orders
- Department-wise spending
- Category-wise spending
- Monthly purchase trends

The dashboard helps management identify important areas that require attention and supports better purchasing and vendor-management decisions.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel Slicers
- Excel Formulas
- Conditional Formatting

---

## 📂 Project Files

| File | Description |
|---|---|
| `Purchase_Vendor_MIS_Dashboard.xlsx` | Final interactive MIS dashboard |
| `Purchase_Vendor_MIS_Raw_Data.xlsx` | Raw purchase and vendor dataset |
| `Problem_Statement.docx` | Project requirements and business questions |
| `README.md` | Project documentation |

---

## 🧹 Data Cleaning & Transformation

The raw dataset contains several real-world data quality issues that commonly occur in organizational MIS data.

The following issues were identified and handled:

- Inconsistent vendor names
- Extra spaces in vendor names
- Duplicate records
- Missing delivery dates
- Invalid received quantity values
- Inconsistent payment status values
- Partial deliveries
- Delayed deliveries
- Purchase amount validation issues
- Missing or incomplete values

Power Query was used to clean, standardize, validate, and transform the raw data before performing analysis.

---

## 🔄 Data Preparation Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Validation
   ↓
Data Transformation using Power Query
   ↓
Calculated Columns
   ↓
PivotTables
   ↓
PivotCharts
   ↓
Slicers & Filters
   ↓
Interactive MIS Dashboard
