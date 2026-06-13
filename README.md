# 💍 Wedlist - Wedding Vendor Management System

A platform to seamlessly connect customers with wedding vendors and manage bookings.*  

![Build](https://img.shields.io/badge/build-passing-brightgreen)  ![License](https://img.shields.io/badge/license-MIT-blue)  ![ASP.NET](https://img.shields.io/badge/framework-ASP.NET-lightblue)  ![Database](https://img.shields.io/badge/database-SQL%20Server-orange)  

---

##  Project Description

The **Wedding Vendor Management System** is an all-in-one platform designed to make wedding planning simple, transparent, and efficient. It allows customers to discover, compare, and book vendors across categories like catering, decoration, venues, and photography, all from a single dashboard. Vendors can register, showcase their services, and manage inquiries, while administrators oversee the entire ecosystem with tools to manage users, listings, and platform activity. By centralizing everything, the system reduces the stress of vendor searches, miscommunication, and scattered processes that couples typically face.

What makes this platform stand out is its **role-based approach**, offering tailored dashboards and features for customers, vendors, and admins. Customers save time with organized vendor discovery and booking, vendors gain visibility and growth opportunities through direct access to clients, and admins maintain quality and security across the system. In essence, it bridges the gap between couples planning their big day and vendors offering their services, creating a smoother, more reliable, and transparent wedding planning experience for everyone involved.


## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Testing](#testing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [FAQs](#faqs)
- [Contact](#contact)

---

## Features
-  Secure login for Admin, Customer, and Vendor  
-  Customer registration and order management  
-  Vendor registration, profile, and inquiry management  
-  Admin dashboard with metrics and management tools  
-  Location-based vendor categorization (state, city, category, subcategory)  
-  Order tracking and inquiry system  
-  Dashboard analytics for each role  

---

##  Technology Stack

- **Frontend**
  - ASP.NET Web Forms (with Master Pages for layout consistency)  
  - HTML5  
  - CSS3 (custom styling + Bootstrap for responsive design)  
  - JavaScript (for interactivity and client-side validation)  
  - jQuery (used for dynamic UI and DOM manipulation)  

- **Backend**
  - ASP.NET Framework (C# Code-behind)  
  - ADO.NET (database connectivity and CRUD operations)  
  - ASP.NET Membership & Authentication (for user login and roles)  
  - Web.config (application configuration management)  

- **Database**
  - Microsoft SQL Server  
  - SQL Server Management Studio (SSMS)  
  - Structured Tables (Customer, Vendor, Admin, Orders, Categories, etc.)  
  - Stored Procedures & Triggers (for optimized queries and automation)  

- **Server**
  - IIS (Internet Information Services for hosting)  
  - Localhost setup for development and testing  

- **Libraries & Modules**
  - System.Data.SqlClient (for SQL Server connection in .NET)  
  - System.Configuration (for managing connection strings)  
  - ASP.NET Validation Controls (for form validation)  
  - Crystal Reports (optional: for generating reports/analytics)  

- **Version Control & Collaboration**
  - Git (version control)  
  - GitHub (repository hosting, collaboration, and issue tracking)  
  - GitHub Projects / Issues (for task management and bug tracking)  

---


##  Installation
1. Install **Visual Studio** with ASP.NET support.  
2. Install **SQL Server** and configure a database.  
3. Clone this repo:  
   ```bash
   git clone https://github.com/Jay-Shah-92/wedlist.git


##  Usage

* Login as **Admin** → Manage customers, vendors, and orders.
* Login as **Customer** → Browse vendors, create orders, and track them.
* Login as **Vendor** → Update profile, respond to inquiries, and track engagement.

---

##  Configuration

* Modify the `Web.config` file to update database connection strings.
* Adjust application settings (like default roles or categories) in the database.

---

##  Testing

* **Manual Testing**:

  1. Register new customer and vendor accounts.
  2. Verify login system and dashboards.
  3. Place an order and validate the database entry.

---

## License

This project is licensed under the [MIT License](LICENSE).  
![License](https://img.shields.io/badge/license-MIT-blue)

---

##  Acknowledgments

* Inspired by the challenges of planning weddings efficiently.
* Built with ASP.NET & SQL Server.

---

##  FAQs

* **Q: Why is my login failing?**
  **A**: Verify that your email and password are correctly registered in the database.

* **Q: How do I deploy this on a live server?**
  **A**: Configure IIS and update your `Web.config` with the production DB connection string.

---

##  Contact

For questions or collaboration:

* **Author**: Jay Shah
* **Email**: [jayshah92.ca@gmnail.com](mailto:jayshah92.ca@gmail.com)
* **GitHub**: [Jay-Shah-92](https://github.com/Jay-Shah-92)
