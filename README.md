# 📊 Supply Chain Analytics Dashboard

## 📌 Project Overview

The **Supply Chain Analytics Dashboard** is an interactive Power BI project developed to analyze and monitor supply chain performance. The dashboard provides valuable insights into sales, customers, products, shipping, and profitability, enabling businesses to make data-driven decisions.

This project follows a **Star Schema Data Model**, improving query performance and making reporting more efficient.

---

## 🎯 Objectives

- Analyze overall sales performance
- Monitor shipping efficiency and delivery delays
- Identify profitable products and categories
- Understand customer purchasing behavior
- Track regional sales performance
- Build an optimized Power BI data model using Fact and Dimension tables

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**
- **CSV**
- **Star Schema Data Modeling**

---

## 📂 Project Structure

```
Milestone1/
│
├── data/
│   ├── Fact_table.csv
│   ├── Dim_Category.xlsx
│   ├── Dim_Customer.xlsx
│   ├── Dim_Date.xlsx
│   ├── Dim_Department.xlsx
│   ├── Dim_Location.xlsx
│   ├── Dim_Product.xlsx
│   └── Dim_Shipping.xlsx
│
├── screenshots/
│   └── Data_model.png
│
├── SupplyChain_Milestone1.pbix
│
└── README.md
```

---

## 🗄️ Dataset

The project uses a Supply Chain dataset containing information about:

- Orders
- Customers
- Products
- Categories
- Departments
- Shipping
- Locations
- Sales
- Profit
- Delivery Status

---

## ⭐ Data Model

The dashboard follows a **Star Schema**.

### Fact Table

- Fact_table

Contains transactional data including:

- Sales
- Profit
- Order Details
- Shipping Details
- Product Information
- Customer Information

### Dimension Tables

- Dim_Category
- Dim_Customer
- Dim_Date
- Dim_Department
- Dim_Location
- Dim_Product
- Dim_Shipping

These tables provide descriptive attributes for filtering and reporting.

---

## 📈 Dashboard Features

The dashboard enables users to:

- View Total Sales
- Analyze Profit
- Monitor Shipping Performance
- Compare Scheduled vs Actual Delivery
- Analyze Product Categories
- Track Customer Segments
- View Regional Sales
- Filter by Date
- Filter by Category
- Filter by Market
- Filter by Shipping Mode

---

## 📊 KPIs

Typical KPIs included in the dashboard:

- Total Sales
- Total Profit
- Total Orders
- Sales per Customer
- Average Shipping Days
- Late Delivery Risk
- Profit Ratio
- Product Performance
- Regional Sales

---

## 📷 Data Model

The project includes the Power BI data model screenshot.

```
screenshots/Data_model.png
```

---

## ⚙️ Power BI Features Used

- Power Query for ETL
- Data Cleaning
- Data Transformation
- Relationship Management
- Star Schema Modeling
- DAX Measures
- Slicers
- Cards
- Charts
- Matrix Visuals
- Interactive Filters

---

## 🚀 How to Use

1. Download the repository.
2. Open **SupplyChain_Milestone1.pbix** using Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the interactive dashboard using slicers and filters.

---

## 📌 Business Insights

This dashboard helps businesses to:

- Identify high-performing products
- Detect delayed shipments
- Monitor profitability
- Improve customer satisfaction
- Optimize inventory decisions
- Improve regional sales strategies
- Support data-driven business decisions

---

## 📚 Skills Demonstrated

- Power BI
- Data Modeling
- Star Schema Design
- DAX
- Power Query
- ETL
- Data Visualization
- Business Intelligence
- Dashboard Design
- Data Analysis

---

## 👨‍💻 Author

**Prudhvi Surla**

Aspiring Data Analyst

### Skills

- Power BI
- SQL
- Excel
- Python
- Data Analysis
- Data Visualization
- Business Intelligence

---

## ⭐ Future Enhancements

- Add Row-Level Security (RLS)
- Implement Incremental Refresh
- Add Forecasting
- Publish to Power BI Service
- Automate Data Refresh
- Add Advanced DAX KPIs
- Create Executive Dashboard
- Build Mobile Layout

---

## 📄 License

This project is intended for educational and portfolio purposes.
