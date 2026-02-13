# LapStore

PROJECT: E-COMMERCE LAPTOP STORE | Apr 2025 – May 2025

# Description:
This is an online e-commerce platform for laptops, with two types of users: Admin and Customer.

Customer: Can browse products, add them to the cart, purchase them, and view their orders.

Admin: Can manage products, categories, pages, website settings, operating systems, colors, and oversee orders (CRUD operations).

# Users Information

Admin: ibrahemtabaneh@gmail.com

Password: 123456

Customer: You can create your own account

# Technologies Used

.NET Core 6

MVC

Design Patterns: Repository Pattern, Unit of Work

Clean Architecture

RESTful API & Swagger

SQL Server

Identity (Authentication & Authorization)

# Additional Notes


Live Website: http://laptopstore1.runasp.net/

# How to Run the Project Locally

1:-Update the Database Connection Settings:

Open appsettings.json

Modify the ConnectionStrings value to match your local SQL Server and database name.

2:-Restore the Database:

Use SQL Server Management Studio (SSMS) to restore the LapShopDB.bak backup file.

Make sure the restored database name matches the one in appsettings.json.

3:-Run the Project:

Open the project in Visual Studio

Click "Restore NuGet Packages" if needed

Run the project using IIS Express or Kestrel

# Database

Source: LapShopDB.bak
