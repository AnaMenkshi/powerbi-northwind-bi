# Power BI Northwind BI Project

**Project:** Implementing a Business Intelligence (BI) System with Power BI  
**Project Member:** Ana Menkshi  


## Project Overview

This project demonstrates the implementation of a Business Intelligence system using **Power BI** connected to a **Northwind SQL Server database**. The goal is to analyze business data and provide actionable insights through interactive reports and visualizations.

We followed these main steps:  
1. Installed SQL Server Developer Edition and SSMS.  
2. Set up and explored the Northwind database.  
3. Installed Power BI Desktop.  
4. Connected Power BI to SQL Server.  
5. Built the **Physical Layer** (data tables, relationships, and cleaning).  
6. Built the **Business Layer** (DAX measures, calculated columns, relationships).  
7. Built the **Presentation Layer** (interactive reports and dashboards).  


## Repository Structure
powerbi-northwind-bi/
├── Northwind_Project.pbix # Main Power BI file
├── docs/
│ ├── step_by_step_setup.docx # Documentation of dashboard creation
│ └── data_dictionary.docx # Data dictionary for all tables and columns
├── README.md # Project overview and instructions
└── .gitignore






> You can use Word documents (`.docx`) for documentation if rich formatting is needed.

---

## Steps Performed

### 1. SQL Server Setup
- Installed SQL Server and SSMS.  
- Created the **Northwind database** with tables and data.  
- Executed queries to explore tables and verify data integrity.

### 2. Power BI Setup
- Connected Power BI Desktop to SQL Server.  
- Imported all tables into Power BI.  
- Defined relationships and cleaned unnecessary columns.  
- Added calculated columns such as:
  - `Employee Full Name`
  - `Expected Days of Delivery`
  - `Remaining Days`
  
### 3. Physical Layer
- Verified table relationships in Model View.  
- Removed irrelevant columns and rows with missing data.  
- Manually formatted dates and merged columns for better reporting.

### 4. Business Layer
- Created **DAX measures** for key metrics, such as:
  - `Net Revenue per Order`
  - `Supplier with Most Products`
  - `Max Sales by Category`
  - `Average Order Cost`
  - `Country with Highest/Lowest Sales`
  - `Customer with Highest Quantity`
- Added calculated columns for discounts, gross revenue, net revenue, seasonal analysis, and inventory metrics.  

### 5. Presentation Layer
- Developed dashboards and visualizations:
  - Cards for key KPIs (Revenue, Orders, Discounts, Losses).  
  - Line and column charts to track sales and orders over time.  
  - Maps showing customer locations with revenue insights.  
  - Matrix visuals for category and product-level performance.  
  - Clustered and stacked bar charts for inventory analysis.  
  - Pie charts for net revenue per category.  
  - Tree maps for low-stock products.  
  - Waterfall charts for employee performance contribution.  
- Added slicers for dynamic filtering by category, product, country, city, employee, and date.  
- Applied conditional formatting for better visual understanding.

---

## Getting Started

1. Open `Northwind_Project.pbix` in **Power BI Desktop**.  
2. Ensure SQL Server is installed and the Northwind database is available.  
3. Connect Power BI to the SQL Server database using the server name provided in your setup.  
4. Load the data and explore dashboards in the report view.

---

## Documentation


---

## License


---

## Author

**Ana Menkshi**








