# Coffee Sales Analysis Dashboard (Excel)

## Project Overview
This project is an end-to-end **Excel-based data analysis and dashboarding solution** built to analyze coffee bean sales data.  
It demonstrates the complete analytics workflow — from data preparation and transformation to visualization and business insights — using **Microsoft Excel**.

The final output is an **interactive, executive-ready sales dashboard** that enables users to explore sales trends, customer behavior, and regional performance.

---

## Business Objective
The goal of this project is to help a coffee retail business:
- Analyze **sales performance over time**
- Identify **top-performing coffee types and roast types**
- Understand **regional sales distribution**
- Evaluate the impact of **customer loyalty programs**
- Identify **high-value customers**

---

## Dataset Description
The Excel workbook contains **three sheets**:

### 1.Orders (1,000 rows)
- Order ID  
- Order Date  
- Customer ID  
- Product ID  
- Quantity  

###  2.Customers (1,000 rows)
- Customer ID  
- Customer Name  
- Email, Phone Number  
- City, Country, Postcode  
- Loyalty Card (Yes/No)  

### 3. Products (48 rows)
- Product ID  
- Coffee Type  
- Roast Type  
- Package Size (Kg)  
- Unit Price  
- Price per 100g  
- Profit  

---

## Data Preparation & Transformation

### Data Integration
- Used **XLOOKUP** to fetch customer details into the Orders sheet
- Used **INDEX–MATCH** to retrieve product information

### Calculations
- Calculated **Sales = Unit Price × Quantity**
- Used **multiple IF functions** to convert coffee and roast type abbreviations into full names

### Formatting
- Custom **date formatting** (dd-MMM-yyyy) to avoid regional date ambiguity
- Custom **number formatting** to display package sizes in Kg
- Currency formatting applied to **Unit Price and Sales**

### Data Quality
- Checked for duplicate records
- Converted data ranges into **Excel Tables** for scalability

---

## Analysis & Pivot Tables

### Total Sales Over Time
- Monthly and yearly sales analysis
- Segmented by **Coffee Type**
- Visualized using a **Line Chart**

### Sales by Country
- Country-wise sales comparison
- Identified top revenue-generating regions
- Visualized using **Bar Charts**

### Top 5 Customers
- Ranked customers based on total sales contribution

---

## Interactive Dashboard Features
The final Excel dashboard includes:

- **Slicers** for:
  - Year
  - Roast Type (Light, Medium, Dark)
  - Package Size (0.2Kg, 0.5Kg, 1Kg, 2.5Kg)
  - Loyalty Card (Yes / No)

- **Charts**:
  - Total Sales Over Time
  - Sales by Country
  - Top 5 Customers

These controls allow users to dynamically filter and explore the data without modifying formulas.

---

## Key Insights
- The **United States** is the highest revenue-generating market
- Sales show **seasonal trends** across years
- Certain coffee types consistently outperform others
- Loyalty card customers contribute significantly to total sales
- A small group of customers drives a large portion of revenue

---

## Skills & Tools Used
- Microsoft Excel  
- XLOOKUP  
- INDEX–MATCH  
- IF functions  
- Pivot Tables & Pivot Charts  
- Slicers & Timelines  
- Data Cleaning & Formatting  
- Dashboard Design & Storytelling  

---

## Final Outcome
A **clean, interactive, and business-ready Excel dashboard** that supports data-driven decision-making related to sales, marketing, and customer strategy.

---

## Project Type
- Excel Data Analysis  
- Business Intelligence  
- Dashboarding & Visualization  

