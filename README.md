# Northwind_DataWarehouse
Data Warehouse based on Northwind Data Base. It was the final semester project for Data Warehouse lecture. Repository includes all Data Flows with lookups designed to create Dimensions and Fact Table.
A package that feeds the Northwind_DW relational data warehouse based on the Northwind database.
The Orders fact table contains the measures Quantity and UnitPrice and is derived from the following tables Order Details and Orders
The Customers dimension table is a copy of the Customers table
The Employees dimension table is created from the Employees table by cutting out attributes: Extension, Photo, ReportsTo, PhotoPath
The Products dimension table is derived from the Products, Category and Suppliers tables and includes Attributes: ProductID, ProductName, CategoryID, CategoryName, SupplierID, CompanyName (name of the supplier)
The dimension table Place-Delivery is created from the Orders table and contains the following attributes ShipID (auto-generated), ShipCity and ShipCountry
Data Warehouse based on Northwind Data Base. It was final semester project. Repo includes Data Flows with lookups in order to create Dimensions and Fact Tables.
