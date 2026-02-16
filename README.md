# 📊 Student Attendance Management System

A simple **Student Attendance Management System** built using **PHP, MySQL, HTML, and CSS**.
This project allows users to add students, mark daily attendance, and automatically calculate monthly attendance percentages.

It is designed as a beginner-friendly project to learn **SQL and database concepts through a real-world application**.

---

## 🚀 Features

✅ Add Student Name and Class
✅ Mark Daily Attendance (Present / Absent)
✅ Store Data in MySQL Database
✅ Monthly Attendance Percentage Calculation
✅ Simple and Clean Interface
✅ Beginner Friendly Code Structure

---

## 🛠️ Technologies Used

* Frontend: HTML, CSS
* Backend: PHP
* Database: MySQL (XAMPP)
* Server: Apache (XAMPP)

---

## 📂 Project Structure

```
attendance-system/
│── index.php            # Home page
│── add_student.php      # Add student form
│── mark_attendance.php  # Attendance entry
│── report.php           # Monthly report
│── db.php               # Database connection
│── style.css            # Styling
│── attendance.sql       # Database file
│── README.md            # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install XAMPP

Download and install XAMPP from:
https://www.apachefriends.org/

### 2️⃣ Start Server

Open XAMPP Control Panel and start:

* Apache
* MySQL

### 3️⃣ Move Project Folder

Copy project folder into:

```
C:\xampp\htdocs\
```

Example:

```
C:\xampp\htdocs\attendance-system
```

### 4️⃣ Create Database

1. Open browser

   ```
   http://localhost/phpmyadmin
   ```
2. Create database:

   ```
   attendance_system
   ```
3. Import the file:

   ```
   attendance.sql
   ```

### 5️⃣ Run Project

Open browser:

```
http://localhost/attendance-system
```

---

## 🧮 Attendance Percentage Logic

The system calculates attendance using SQL queries:

```
Percentage = (Total Present Days / Total Working Days) × 100
```

---

## 🎯 Learning Objectives

This project helps in understanding:

* Database Design
* SQL Queries (CRUD Operations)
* Primary & Foreign Keys
* PHP–MySQL Connection
* Real-World Application Development

---

## 📈 Future Improvements

* Login Authentication System
* Admin Dashboard
* Export to Excel / PDF
* Graphical Reports
* Responsive UI

---

## 👨‍💻 Author

**Adithya S Shetty**
BCA Student | Aspiring Software Developer

---

## ⭐ Contribution

Feel free to fork this repository and improve the project.

---

## 📜 License

This project is open-source and available for learning purposes.
