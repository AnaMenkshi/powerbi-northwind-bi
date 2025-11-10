## Complete guide for setting up and running the BI project. Follow these steps to get started:  
**1.Step 1: Install SQL Server and SSMS**

    1. Install **SQL Server Developer Edition**.  
    2. Install **SQL Server Management Studio (SSMS)**.  

---

**2. Step 2: Set Up Northwind Database**

    1. Download the Northwind script `instnwnd.sql` from:  
      [Microsoft GitHub - Northwind](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs)
    2. Open **SSMS** and connect to your SQL Server instance.  
    3. Open the script `instnwnd.sql` in a new query window.  
    4. Execute the script to create and populate the Northwind database.  

     > Tip: After execution, you can verify the database by running:  
    ```sql
      SELECT TABLE_NAME  
      FROM INFORMATION_SCHEMA.TABLES  
      WHERE TABLE_TYPE = 'BASE TABLE'  
      AND TABLE_CATALOG = 'Northwind';




**3.Explore the Northwind database: check tables, relationships, and sample data.**

**4.Install Power BI Desktop and connect it to the SQL Server database.**

**5.Implement the Physical Layer:**

    Import tables from SQL Server.

    Verify and adjust relationships.

    Clean unnecessary data and add custom columns.

**6.Implement the Business Layer:**

    Create DAX measures and calculated columns.

    Ensure correct relationships between tables for accurate calculations.

**7.Develop the Presentation Layer:**

    Build interactive visualizations, charts, slicers, matrices, and dashboards.

    Apply conditional formatting and optimize layout.

    Perform inventory and sales analysis using the built visualizations.

##### This guide ensures a fully functional Power BI solution ready for analysis and reporting.




