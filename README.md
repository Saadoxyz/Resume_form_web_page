
# 📄 Resume Form Application (.NET + SQL Server)

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=14F195&center=true&vCenter=true&width=600&lines=Build+Your+Professional+Resume;Securely+Store+Career+Details+in+SQL+Server;Developed+in+.NET+WinForms+by+Saad+Khan" alt="Typing SVG" />
</div>

<div align="center">
  
![Tech Stack](https://img.shields.io/badge/Tech-.NET-blueviolet?style=for-the-badge&logo=dotnet&logoColor=white)
![Database](https://img.shields.io/badge/Database-SQL%20Server-red?style=for-the-badge&logo=microsoftsqlserver)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge&logo=checkmarx)
![License](https://img.shields.io/badge/License-MIT-1abc9c?style=for-the-badge)
![Author](https://img.shields.io/badge/Made%20By-Saad%20Khan-1DA1F2?style=for-the-badge&logo=github)

</div>

---

## 📌 Project Overview

The **Resume Form Application** is a robust Windows Forms desktop project created using **C# (.NET Framework)** and **SQL Server**. It allows users to fill out detailed professional resumes and store them securely in a database. The project was built with beginner-friendly code and clean UI design, ideal for job applicants, HR teams, or university projects.

🧩 It covers all key resume fields: personal info, education, experience, skills, projects, and references.

🛡️ Data is safely stored in SQL Server using secure ADO.NET-based connectivity.

---

## ✨ Features

- 📝 Personal & Contact Details Form  
- 🎓 Education, Certifications & Qualifications  
- 💼 Work Experience & Project Descriptions  
- 💬 Skills, Interests, and Languages  
- 📧 Optional Upload Field for PDF Resume  
- 🗄️ Stores records in SQL Server with timestamps  
- 🛡️ Input validation and clean error handling  
- 🖨️ Ready-to-Print resume output template *(optional)*

---

## 🧱 Technologies Used

| Category     | Tech Stack                         |
|--------------|------------------------------------|
| Language     | `C# (.NET Framework)`              |
| Platform     | `Windows Forms (WinForms)`         |
| Backend DB   | `SQL Server 2019 / LocalDB`        |
| Connector    | `ADO.NET`                          |
| IDE          | `Visual Studio 2019/2022`          |

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/saadoxyz/resume-form-dotnet.git
````

2. **Open Project in Visual Studio**

   * Launch `ResumeForm.sln`

3. **Setup SQL Server**

   * Run the SQL script in `/database/resume_schema.sql` to create the DB and table
   * Update your `App.config` with your DB connection string

4. **Build & Run**

   * Hit `F5` or click `Start` to launch the app

---

## 🧩 Database Table Structure

```sql
CREATE TABLE ResumeData (
  ID INT PRIMARY KEY IDENTITY,
  FullName NVARCHAR(100),
  Email NVARCHAR(100),
  Phone NVARCHAR(15),
  Education NVARCHAR(MAX),
  Experience NVARCHAR(MAX),
  Skills NVARCHAR(MAX),
  References NVARCHAR(MAX),
  CreatedAt DATETIME DEFAULT GETDATE()
);
```

## 📬 Author & Contact

| Name      | Email                                                 | GitHub Profile                           |
| --------- | ----------------------------------------------------- | ---------------------------------------- |
| Saad Khan | [saado652004@gmail.com](mailto:saado652004@gmail.com) | [@saadoxyz](https://github.com/saadoxyz) |

---

## 🧠 Use Case Scenarios

* 🧑‍💼 **HR Systems:** Easily gather structured resume data
* 🎓 **University Projects:** Great for students learning .NET + SQL
* 🧾 **Digital Resume Portals:** Extend to generate PDF resumes or connect with job boards

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&text=Happy+Coding!&fontColor=ffffff&fontSize=30" />
</div>
```
