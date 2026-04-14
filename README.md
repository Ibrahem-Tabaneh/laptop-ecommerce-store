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

 ## 📸 Project Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/7abed7e0-5872-4312-8ba5-3080393cfeda" width="48%" alt="Screenshot 1" />
  <img src="https://github.com/user-attachments/assets/7a8be36b-76b5-4ad1-811b-728cb5ed15bb" width="48%" alt="Screenshot 2" />
</div>

<br />

<div align="center">
  <img src="https://github.com/user-attachments/assets/85e5dc31-a5e3-4530-8173-b1cb596e7ad8" width="97%" alt="Screenshot 3" />
</div>



📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/ibrahem-tabaneh-249683249)
