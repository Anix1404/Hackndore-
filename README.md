Introduction
Welcome to our Municipality Inventory Management System (MIMS), a cutting-edge solution meticulously designed to revolutionize your inventory operations. Powered by ASP.NET Core 8.0 Razor Pages (C#), MIMS offers a comprehensive suite of features including Sales, Purchase, Delivery, Goods Receive, Transfer, Adjustment, Return, Scrapping, Stock Count, Transaction Report, Movement Report, and Stock Report. Seamlessly manage your municipality inventory with ease and precision, ensuring optimal stock levels, streamlined workflows, and enhanced productivity. Experience the future of inventory management with MIMS – your ultimate tool for operational excellence.

Technical Features
ASP.NET Core 8.0 Razor Pages (C#)
ASP.NET Identity Users / Roles
EF Core / LINQ
OData based API (Server side: paging, filter, search, sort)
Clean Architecture
Repository Pattern
Email
WkHtmlToPdf
Upload / Download Images
AutoMapper
NumberSequence
Functional Features
Customer Group
Customer Category
Customer
Customer Contact
Sales Order
Sales Report
Vendor Group
Vendor Category
Vendor
Vendor Contact
Purchase Order
Purchase Report
Unit Measure
Product Group
Product
Warehouse
Delivery Order
Sales Return
Goods Receive
Purchase Return
Transfer
Adjustment
Scrapping
Stock Count
Transaction Report
Stock Report
Movement Report
Company Settings
Tax
User Profile
User List
Number Sequence
Error Log
Analytic Log
Authentication / Membership
Run The Project: Visual Studio
This project is an ASP.NET project, so every official documentation or tutorial related to ASP.NET will also apply. Follow these steps:

Open the project using Visual Studio.
Change the connection string (appsettings.json) to target your MS SQL Server.
Right Click Clean.
Right Click Build.
Run the project by clicking the green play button on your Visual Studio toolbar.
Note: The project will automatically create the database if it does not already exist.

Run The Project: IIS Web Server
Follow the steps below:

Convert the source code to distributable by right-clicking and selecting publish. Place the files in a folder of your choice.
Transfer the files from the first step to IIS.
Tips:

Ensure there are no issues connecting to the database server from your web server.
