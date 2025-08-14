#  🚚 Transportation Management System (ASP.NET Web Forms)
# A full-stack ASP.NET Web Forms application for B2B logistics, allowing:
# 1.User and Admin registration/login
# 2. Fleet (Vehicle) management
# 3. Booking and delivery tracking
# \## 📁 Project Structure
# ```
#.vs/
#packages/
#Transportation-Management-System.sln
# Transportation-Management-System/
#App_Data/
#bin/
#Models/
#obj/
#Properties/
#Global.aspx
#Global.aspx.cs
#packages.config
#Transportation-Management-System.csproj
#Transportation-Management-System.csproj.user
#Web.config
#Web.Debug.config
#Web.Release.config
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
# ├── Home.aspx / Home.aspx.cs(contect page)
# ```

#  🧠 Technologies Used
# 1. ASP.NET Web Forms (C#)
# 2. SQL Server (LocalDB)
# 3. ADO.NET (with `SqlConnection`, `SqlCommand`)
# 4. App\_Themes with `.skin` files (no inline CSS)
# 5. BCrypt.Net for secure password hashing

#  🔐 Authentication
# 1. Unified Login/Register form (like `login.tsx`)
# 2. Roles: `user`, `admin`
# 3. Admins must provide a city (e.g., Ahmedabad)

#  💾 Databases
# 1. `Userdb`: Handles all user accounts
# \- `Admindb`: Stores bookings, vehicles, admin operations

#  📦 Features
# \- Responsive UI using ASP.NET controls + App\_Themes
# \- MultiView toggle for Register/Login forms
# \- Role-based redirection after login
# \- Session, Cookies, and basic caching support

#  🚀 Getting Started
# 1. Clone or open in Visual Studio 2022
# 2. Set `Site1.master` as the starting master page
# 3\. Set `Login.aspx` as the start page
# 4\. Restore NuGet packages:`BCrypt.Net-Next`
# 5\. Run SQL scripts to create `Userdb` and `Admindb` tables
# 6\. Build and Run with debug

#  🧪 Test Accounts
# You can register new accounts.
# 1. For Admin: choose `Admin` and select a city

#  📄 SQL Schema Sample
# ```sql

# CREATE TABLE Users (
# Id UNIQUEIDENTIFIER PRIMARY KEY,
# Name NVARCHAR(100),
# &nbsp; Username NVARCHAR(50),
# &nbsp; Email NVARCHAR(100),
# &nbsp; Password NVARCHAR(MAX),
# &nbsp; Role NVARCHAR(20),
# &nbsp; Phone NVARCHAR(20),
# &nbsp; City NVARCHAR(100),
# &nbsp; CreatedAt DATETIME
# );

# ```

#  📧 Contact
# Made by [Prof. Jinesh Parasbhai Shah]


