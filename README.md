# 🌍 Travel Trip Project

![ASP.NET MVC](https://img.shields.io/badge/ASP.NET-MVC-blue)
![C#](https://img.shields.io/badge/C%23-.NET-purple)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-ORM-green)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-red)

A web-based travel blog and tourism management platform developed with ASP.NET MVC 5 and Entity Framework.

## 🚀 Technologies Used

* ASP.NET MVC 5
* C#
* Entity Framework
* SQL Server
* Bootstrap
* Partial Views
* HTML5
* CSS3

## ✨ Features

👤 Visitor Features
* View the most popular blog posts on the homepage
* Explore administrator's featured destinations
* Browse travel blog content
* View detailed blog posts
* Leave comments on blog articles
* Send messages through the contact form

🔐 Admin Panel Features
* Secure authentication system
* Create, update, and delete blog posts
* Manage visitor comments
* View all blogs and comments from a centralized dashboard
* Protected admin panel using ASP.NET MVC Authorization

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/Kaandalgar/TravelTripProject.git
```

2. Open the solution file in Visual Studio

```txt
TravelTripProje.sln
```

3. Update the SQL Server connection string in `Web.config`

```xml
<connectionStrings>
  <add name="Context"
       connectionString="Data Source=YOUR_SERVER_NAME; Initial Catalog=TravelDb; Integrated Security=True;"
       providerName="System.Data.SqlClient" />
</connectionStrings>
```

4. Open Package Manager Console and run the migration/database command if needed

```powershell
Update-Database
```

5. Run the project with IIS Express or press `F5`.

## 📌 Notes

* This project uses Entity Framework Code First.
* The database name is `TravelDb`.
* The connection string should be updated according to the local SQL Server instance.
* The admin panel is protected using Forms Authentication.
* The UI is based on a customized ready-made theme.
* Blog content, comments, and site data are dynamically managed through the database.

## 📸 Screenshots

### Home Page

![Home Page](images/1.png)

### Blog Page

![Blog Page](images/2.png)

### Blog Detail

![Blog Detail](images/3.png)

### Blog Detail & Content View

![Blog Detail](images/4.png)

### Comment System

![Comment System](images/5.png)

### Admin Panel - Blog Management

![Admin Blog Management](images/admin1.png)

### Admin Panel - Comment Management

![Admin Comment Management](images/admin2.png)

### Login Page

![Login Page](images/login1.png)

## 🎯 Purpose

This project was developed as part of my ASP.NET MVC learning journey to gain hands-on experience with MVC architecture, Entity Framework, SQL Server integration, authentication, CRUD operations, and admin panel development.

## 👨‍💻 Developer

**İbrahim Kaan Dalgar**
Software Engineer

GitHub: (https://github.com/Kaandalgar)

LinkedIn: (https://www.linkedin.com/in/kaan-dalgar)
