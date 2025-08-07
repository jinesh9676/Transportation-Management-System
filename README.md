# \# 🚚 Transportation Management System (ASP.NET Web Forms)

# 

# A full-stack ASP.NET Web Forms application for B2B logistics, allowing:

# \- User and Admin registration/login

# \- Fleet (Vehicle) management

# \- Booking and delivery tracking

# 

# \## 📁 Project Structure

# 

# ```

# Transportation-Management-System/

# ├── App\_Themes/

# │   └── App\_Themes.skin

# ├── Models/

# │   ├── User.cs

# │   ├── Vehicle.cs

# │   └── Booking.cs

# ├── DAL/

# │   ├── UserDAL.cs

# │   ├── AdminDAL.cs

# │   ├── BookingDAL.cs

# │   └── VehicleDAL.cs

# ├── Site1.master

# ├── Site1.master.cs

# ├── Login.aspx / Login.aspx.cs

# ├── Register.aspx / Register.aspx.cs

# ├── Home.aspx / Home.aspx.cs

# ├── Dashboard.aspx (user)

# └── AdminDashboard.aspx (admin)

# ```

# 

# \## 🧠 Technologies Used

# \- ASP.NET Web Forms (C#)

# \- SQL Server (LocalDB)

# \- ADO.NET (with `SqlConnection`, `SqlCommand`)

# \- App\_Themes with `.skin` files (no inline CSS)

# \- BCrypt.Net for secure password hashing

# 

# \## 🔐 Authentication

# \- Unified Login/Register form (like `login.tsx`)

# \- Roles: `user`, `admin`

# \- Admins must provide a city (e.g., Ahmedabad)

# 

# \## 💾 Databases

# \- `Userdb`: Handles all user accounts

# \- `Admindb`: Stores bookings, vehicles, admin operations

# 

# \## 📦 Features

# \- Responsive UI using ASP.NET controls + App\_Themes

# \- MultiView toggle for Register/Login forms

# \- Role-based redirection after login

# \- Session, Cookies, and basic caching support

# 

# \## 🚀 Getting Started

# 1\. Clone or open in Visual Studio 2022

# 2\. Set `Site1.master` as the starting master page

# 3\. Set `Login.aspx` as the start page

# 4\. Restore NuGet packages:

# &nbsp;  - `BCrypt.Net-Next`

# 5\. Run SQL scripts to create `Userdb` and `Admindb` tables

# 6\. Build and Run

# 

# \## 🧪 Test Accounts

# You can register new accounts.

# \- For Admin: choose `Admin` and select a city

# 

# \## 📄 SQL Schema Sample

# ```sql

# CREATE TABLE Users (

# &nbsp; Id UNIQUEIDENTIFIER PRIMARY KEY,

# &nbsp; Name NVARCHAR(100),

# &nbsp; Username NVARCHAR(50),

# &nbsp; Email NVARCHAR(100),

# &nbsp; Password NVARCHAR(MAX),

# &nbsp; Role NVARCHAR(20),

# &nbsp; Phone NVARCHAR(20),

# &nbsp; City NVARCHAR(100),

# &nbsp; CreatedAt DATETIME

# );

# ```

# 

# \## 📧 Contact

# Made by \[Prof. Jinesh Parasbhai Shah]

