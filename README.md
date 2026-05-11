# 🏥 Hospital Management System

A desktop-based Hospital Management System built with **C# Windows Forms** and **SQL Server**, designed to digitalise and streamline core hospital administrative operations.

---

## 📋 Overview

This system provides hospital staff with a centralised platform to manage patients, doctors, rooms, lab records, billing, and reporting — replacing manual paper-based processes with an efficient digital workflow.

---

## ✨ Features

| Module | Description |
|---|---|
| 🔐 **Authentication** | Secure admin login with SQL Server credential validation |
| 👤 **Patient Management** | Register, update, and manage patient records |
| 👨‍⚕️ **Doctor Management** | Maintain doctor profiles and assignments |
| 🛏️ **In-Patient Module** | Manage admitted patients and ward assignments |
| 🚶 **Out-Patient Module** | Track and manage outpatient visits and consultations |
| 🧪 **Laboratory Module** | Record and manage lab test requests and results |
| 🛏️ **Room Management** | Track room availability and patient-room assignments |
| 💳 **Billing Module** | Calculate and generate bills based on doctor, medicine, and room charges |
| 📊 **Reports** | Generate detailed reports for patients, doctors, billing, lab, rooms, and patient types |

---

## 🛠️ Tech Stack

- **Language:** C# (.NET Framework)
- **UI Framework:** Windows Forms (WinForms)
- **Database:** Microsoft SQL Server
- **IDE:** Visual Studio
- **Reporting:** Crystal Reports / RDLC

---

## ⚙️ Getting Started

### Prerequisites

- Visual Studio 2019 or later
- Microsoft SQL Server (local instance)
- .NET Framework 4.x

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/reabetswe-lentoa/hospital-management-system.git
   ```

2. **Set up the database**
   - Open SQL Server Management Studio (SSMS)
   - Create a new database named `hospital`
   - Run the provided SQL script to create the required tables

3. **Configure the connection string**
   - Open `App.config`
   - Update the connection string if your SQL Server instance name differs:
     ```xml
     <connectionString>Data Source=.;Initial Catalog=hospital;Integrated Security=True</connectionString>
     ```

4. **Build and run**
   - Open `hospital_management_system.sln` in Visual Studio
   - Build the solution (`Ctrl + Shift + B`)
   - Run the project (`F5`)

---

## 🗄️ Database Tables

The system uses the following core tables:

- `admin` — login credentials
- `patient` — patient registration records
- `doctor` — doctor profiles
- `inpatient` — admitted patient records
- `outpatient` — outpatient visit records
- `lab` — laboratory test records
- `room` — room availability and assignments
- `bill` — billing records (doctor charge, medicine charge, room charge, number of days)

---

## 📸 Screenshots

> _Add screenshots of the login screen, dashboard, and key modules here_

---

## 🚀 Future Improvements

- Migrate from WinForms to a web-based interface using ASP.NET Core and React
- Implement role-based access control (Admin, Doctor, Nurse, Receptionist)
- Add appointment scheduling and notification system
- Integrate medical inventory and pharmacy management
- Replace raw SQL queries with Entity Framework for improved security and maintainability

---

## 👨‍💻 Author

**Reabetswe Lentoa**  
Software Developer | C# · .NET · React · SQL Server  
[LinkedIn](https://linkedin.com/in/reabetswe-lentoa) · [GitHub](https://github.com/reabetswe-lentoa)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
