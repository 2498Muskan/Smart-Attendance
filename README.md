# 🎓 College Smart Attendance Management System

A smart, web-based attendance management system built using **React.js, Node.js, Express.js, and MySQL**. It helps colleges efficiently manage students, teachers, classes, sections, and daily attendance through a centralized dashboard.

## 🚀 Key Features

- **Admin Dashboard:** Manage teachers, students, departments, classes, and sections.
- **Teacher Management:** Assign teachers to multiple sections.
- **Student Management:** Add, update, and manage student records.
- **Smart Attendance:** Mark students as Present or Absent with a simple roll-number-based process.
- **CSV Import:** Upload student records using CSV files.
- **Attendance Reports:** View and manage attendance records.
- **Database Integration:** Store and retrieve attendance data using MySQL.
- **Role-Based Access:** Separate access for administrators and teachers.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js, Vite |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Database Management | phpMyAdmin |
| API Communication | REST API |
| Styling | CSS |

## 📁 Project Structure

```text
College-Smart-Attendance/
│
├── client/                 # React frontend
│
├── server/                 # Node.js backend
│   ├── src/
│   ├── package.json
│   └── .env.example
│
├── database/
│   └── schema.sql          # Database structure
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/2498Muskan/Smart-Attendance.git
cd Smart-Attendance
```

### 2. Configure the Database

1. Start Apache and MySQL using XAMPP.
2. Open phpMyAdmin: http://localhost/phpmyadmin
3. Import `database/schema.sql`.
4. Ensure the database is created successfully.

### 3. Configure the Backend

Open the server directory:

```bash
cd server
npm install
```

Copy `.env.example` to `.env` and configure your MySQL credentials.

Then execute:

```bash
npm run seed
npm run dev
```

### 4. Configure the Frontend

Open another terminal:

```bash
cd client
npm install
npm run dev
```

### 5. Launch the Application

Open your browser:

**http://localhost:5173**

## 🔐 Demo Login Credentials

| Role | Email | Password |
|---|---|---|
| Admin | admin@example.com | admin123 |
| Teacher | teacher@example.com | teacher123 |

*These are sample development credentials. Change them before deploying the application.*

## 📋 Attendance Instructions

### CSV Upload Format

Use the following column headers:

```csv
Roll Number,Student Name
```

### Marking Attendance

- Enter only the roll numbers of students who are present.
- Students whose roll numbers are not entered will automatically be marked absent.
- You can enter short IDs (X1, X2) or complete roll numbers.
- Teachers can manage attendance for multiple assigned sections.

## 🎯 Project Objective

The main objective of this project is to simplify traditional attendance management in colleges by providing a digital platform that improves accuracy, reduces manual work, and makes attendance records easier to manage.

## 👩‍💻 Developed By

**Muskan**

College Smart Attendance Management System

---

⭐ If you find this project useful, consider giving the repository a star on GitHub!

**GitHub Repository:**  
https://github.com/2498Muskan/Smart-Attendance
