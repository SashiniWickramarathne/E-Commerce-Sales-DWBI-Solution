# E-Commerce Sales Data Warehouse & Business Intelligence Solution

> A complete Business Intelligence (BI) solution built using **SQL Server Analysis Services (SSAS)** and **Power BI** to transform transactional e-commerce sales data into interactive dashboards and multidimensional analytics.

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SSAS](https://img.shields.io/badge/SSAS-Analysis%20Services-blue?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

#  Project Overview

This project demonstrates the implementation of a complete **Business Intelligence solution** using an **E-Commerce Sales Data Warehouse**. It covers the end-to-end process of building a multidimensional analytical system, from designing the data warehouse to creating interactive Power BI dashboards.

The solution includes:

- Designing an OLAP Cube using SQL Server Analysis Services (SSAS)
- Creating multidimensional hierarchies
- Developing Key Performance Indicators (KPIs)
- Performing OLAP operations
- Building interactive Power BI reports
- Publishing reports to Power BI Service

This project enables efficient business analysis by allowing users to explore sales performance, customer behavior, and product insights from multiple dimensions.

---

#  Objectives

- Build a multidimensional OLAP Cube using SSAS.
- Design dimension hierarchies for efficient navigation.
- Develop KPIs for business performance analysis.
- Demonstrate common OLAP analytical operations.
- Create interactive Power BI dashboards.
- Enable data-driven business decision making.

---

#  Dataset

The project uses an **E-Commerce Sales Transactions Dataset** containing transactional information including:

- Customer Details
- Product Information
- Orders
- Sales
- Profit
- Discounts
- Regions
- Dates

### Data Warehouse Schema

#### Dimension Tables

- DimCustomer
- DimProduct
- DimDate

#### Fact Table

- FactSales

### Measures

- Sales Amount
- Profit
- Quantity Sold
- Discount

---

#  System Architecture

```text
E-Commerce Dataset
        │
        ▼
SQL Server Data Warehouse
        │
        ▼
SQL Server Analysis Services (SSAS)
        │
        ▼
      OLAP Cube
        │
 ┌──────┴────────┐
 ▼               ▼
Excel        Power BI
        │
        ▼
Business Insights
```

---

#  Technologies Used

| Technology | Purpose |
|------------|---------|
| SQL Server | Data Warehouse |
| SQL Server Analysis Services (SSAS) | OLAP Cube Development |
| SQL Server Data Tools (SSDT) | Cube Design |
| Microsoft Excel | OLAP Analysis |
| Power BI Desktop | Dashboard Development |
| Power BI Service | Dashboard Publishing |

---

#  Features

##  SSAS Cube Development

- Data Source Creation
- Data Source View (DSV)
- Cube Design
- Measure Groups
- Dimension Creation
- Hierarchy Design
- KPI Development
- Cube Deployment

---

##  Dimension Hierarchies

### Date Hierarchy

```text
Year
 └── Quarter
      └── Month
           └── Date
```

### Product Hierarchy

```text
Category
 └── SubCategory
      └── Product
```

### Customer Hierarchy

```text
Country
 └── Region
      └── State
           └── City
```

---

#  Key Performance Indicators (KPIs)

The OLAP Cube includes business KPIs such as:

-  Total Sales
-  Profit Margin
-  Order Count

These KPIs provide quick insights into business performance and support strategic decision-making.

---

#  OLAP Operations Demonstrated

###  Roll-Up

Aggregates detailed data into summarized information.

Example:

```
Month → Year
```

---

###  Drill-Down

Navigates from summarized data into more detailed information.

Example:

```
Year → Quarter → Month → Day
```

---

###  Slice

Filters data using a single dimension.

Example:

```
Region = West
```

---

###  Dice

Filters data using multiple dimensions simultaneously.

Example:

```
Region = West
Category = Furniture
Year = 2023
```

---

###  Pivot (Rotate)

Changes the orientation of the cube to analyze data from different perspectives.

---

#  Power BI Reports

The project includes multiple interactive dashboards:

###  Report 1

- Matrix Report
- Sales Summary

###  Report 2

- Cascading Slicers
- Multiple Interactive Visualizations
- Dynamic Filtering

###  Report 3

- Slice Report
- Drill-Through Navigation
- Detailed Transaction Analysis

---

#  Project Structure

```text
📦 E-Commerce-BI-Project
│
├── 📂 SSAS Project
│   ├── Data Source
│   ├── Data Source View
│   ├── Cube
│   ├── Dimensions
│   └── KPIs
│
├── 📂 Power BI
│   ├── Dashboard.pbix
│   └── Reports
│
├── 📂 Excel
│   └── OLAP_Report.xlsx
│
├── 📂 Screenshots
│
├── 📄 Report.pdf
│
└── 📄 README.md
```

---

#  Screenshots

Include screenshots of:

- Data Warehouse Schema
- SSAS Cube
- Cube Browser
- KPI Dashboard
- Roll-Up Operation
- Drill-Down Operation
- Slice Operation
- Dice Operation
- Pivot Analysis
- Power BI Dashboard

---

#  Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Warehousing
- SQL Server Analysis Services (SSAS)
- OLAP Cube Development
- Multidimensional Data Modeling
- KPI Design
- Business Intelligence
- Power BI Dashboard Development
- Interactive Data Visualization
- Decision Support Systems

---

#  Future Improvements

- Implement Incremental Data Loading
- Add Predictive Sales Analytics
- Integrate Machine Learning Models
- Real-time Dashboard Updates
- Azure Cloud Deployment
- Advanced Power BI Analytics

---

#  Academic Information

**Module:** IT3021 – Data Warehousing & Business Intelligence

**Institution:** Sri Lanka Institute of Information Technology (SLIIT)

---

#  Author

**Sashini Bhagya Wickramarathne**

 Data Science Undergraduate  
 Sri Lanka Institute of Information Technology (SLIIT)


---
