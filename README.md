# 🏨 Hostel Management System

A web-based application designed to simplify and automate hostel operations such as student registration, room allocation, complaint tracking, and administrative management.

## 🚀 Overview
The **Hostel Management System (HMS)** helps digitize everyday hostel processes.  
It provides different roles and interfaces for:

- **Students**
- **Warden/Admin**
- **Staff** (optional)

---

## 🛠️ Tech Stack

### **Backend**
- Python (Django Framework)
- Django REST Framework (optional)
- SQLite / MySQL / PostgreSQL

### **Frontend**
- HTML, CSS, JavaScript  
- Bootstrap / Tailwind CSS (if used)

### **Other Tools**
- Django ORM  
- Django Authentication System  
- REST APIs

---

## ✨ Features

### 👨‍🎓 Student Module
- Login/signup with secure authentication  
- View/edit profile  
- Room allocation request and status  
- File and track complaints  
- View hostel notices  
- Payment history (optional)

### 🏫 Admin/Warden Module
- Manage students, staff, and rooms  
- Allocate/modify rooms  
- Track all complaints and update statuses  
- Add/edit/delete notices  
- Generate reports (occupancy, complaints, etc.)

### 🛠 Staff Module *(Optional)*
- View assigned tasks  
- Update progress on complaint tickets  

---

## 📂 Project Structure
hostel_management/
│
├── hostel/                 # Main Django project settings
├── students/               # Student app
├── admin_panel/            # Admin/Warden app
├── complaints/             # Complaint module
│
├── static/                 # CSS, JS, Images
├── templates/              # Shared templates (base.html, login.html)
│
├── db.sqlite3              # Database (if using SQLite)
└── manage.py
---

👤 Author

Kavya Bhatiya
B.Tech in AI | SVNIT Surat
