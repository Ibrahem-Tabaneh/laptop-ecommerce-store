# 💻 Laptop E-Commerce Store (ASP.NET Core MVC)

A robust e-commerce web application dedicated to laptops, developed using the ASP.NET Core MVC architectural pattern and industry-standard design patterns to ensure scalability and maintainable code.

## 🌐 Live Demo
**Link:** [Check the Live Site Here] (http://laptopstore1.runasp.net/)


## 🚀 Tech Stack

- **Framework:** ASP.NET Core 6.0 (MVC)
- **Security:** ASP.NET Core Identity (Authentication & Authorization)
- **Database:** Microsoft SQL Server
- **ORM:** Entity Framework Core
- **Frontend:** Razor Views, HTML5, CSS3, Bootstrap, and JavaScript.

## 🏗️ Architecture & Best Practices

- **Repository Pattern:** Abstracted data access layer to decouple business logic from the database, making the code more testable and organized.
- **Identity Framework:** Managed user registration, login, and Role-Based Access Control (RBAC).
- **Partial Views:** Optimized UI by using Partial Views for reusable components (e.g., Product Cards), ensuring cleaner and more maintainable Razor code (DRY Principle).
- **MVC Pattern:** Logical separation between UI (Razor), Business Logic (Controllers), and Data (Models).

## 👥 User Roles & Permissions

### 🔑 Admin Credentials (For Testing)
- **Email:** `ibrahemtabaneh@gmail.com`
- **Password:** `123456`

**Admin Features:**
- Access to the **Admin Dashboard**.
- Full CRUD operations: Add, Edit, and Delete laptop products.
- Monitoring and managing customer orders.

### 👤 Customer Features
- **Self-Registration:** New users can securely create their own accounts.
- **Smart Suggestions:** Displays related products based on price range for a better shopping experience.
- **Shopping Cart:** Full functionality to add, update, and manage items before checkout.
- **Order Management:** Securely place and track personal order history.

## 🗄️ Database Management

- **Entity Framework Migrations:** The database schema is fully managed via EF Core Migrations.
- **Setup:** Once the connection string is configured in `appsettings.json`, simply run `Update-Database` in the Package Manager Console to generate the full schema.


📫 **Connect with me:** [LinkedIn](www.linkedin.com/in/ibrahem-tabaneh-249683249)
