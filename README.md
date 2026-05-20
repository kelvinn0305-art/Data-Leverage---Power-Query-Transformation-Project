# 📊 Power BI / Power Query Data Transformation Project

## 🚀 Project Overview
This project demonstrates advanced **Power Query transformations** and **data preparation techniques** using Microsoft Power BI. The goal of this project is to clean, transform, merge, analyze, and prepare multiple datasets for reporting and business insights.

The project covers:
- Data Extraction
- Data Cleaning
- Text Transformations
- Date & Time Functions
- Conditional Columns
- Pivoting & Unpivoting
- Data Merging & Appending
- Aggregations
- Data Profiling
- Parameters & Refresh Simulation

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| Microsoft Power BI | Data Visualization & Reporting |
| Power Query Editor | Data Cleaning & Transformation |
| Excel Files (.xlsx) | Source Data |
| HTML Web Tables | External Data Extraction |

---

# 📂 Project Files

| File Name | Description |
|-----------|-------------|
| `Sales_Jan.xlsx` | January Sales Data |
| `Sales_Feb.xlsx` | February Sales Data |
| `Sales_Mar.xlsx` | March Sales Data |
| `Employee_Data.xlsx` | Employee Information |
| `Project.pbix` | Main Power BI Project File |

---

# ✅ Project Tasks & Requirements

## 1️⃣ Data Extraction

### Tasks Performed
- Loaded an **HTML table from the web**
- Imported multiple Excel files from a folder:
  - `Sales_Jan.xlsx`
  - `Sales_Feb.xlsx`
  - `Sales_Mar.xlsx`
- Imported employee data containing:
  - EmployeeID
  - Name
  - Department
  - Region
  - Join Date

### Features Used
- Web Connector
- Folder Connector
- Excel Workbook Connector

---

## 2️⃣ Basic Transformations

### Tasks Performed
- Removed blank rows and columns
- Promoted first row as headers
- Renamed columns to meaningful names
- Changed data types appropriately
- Removed duplicates
- Filtered null values

### Power Query Features Used
- Remove Rows
- Remove Columns
- Promote Headers
- Change Type with Locale
- Remove Duplicates
- Filter Rows

---

## 3️⃣ Text Tools

### Functions Used
- `UPPER()`
- `LOWER()`
- `TRIM()`
- `CLEAN()`
- `REPLACE()`
- `Split Column by Delimiter`

### Tasks Performed
- Standardized customer names
- Cleaned address fields
- Removed unnecessary spaces
- Corrected inconsistent text formatting

---

## 4️⃣ Numeric Tools

### Tasks Performed
- Rounded revenue columns to 2 decimal places
- Created calculated profit column

### Profit Formula

```text
Profit = Revenue - Cost
