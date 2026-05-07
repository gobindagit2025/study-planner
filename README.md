# 📚 Student Study Planner Management System

A modern full-stack web application built for students to efficiently manage subjects, assignments, study schedules, and daily academic tasks.

This project helps students stay organized with task tracking, subject management, progress monitoring, and a clean responsive dashboard.

---

# 🚀 Live Features

* 🔐 Secure Login & Registration System
* 📊 Student Dashboard with Progress Tracking
* 📖 Subject Management
* ✅ Task Management System
* ✏️ Edit / Delete Tasks
* 📅 Due Date Tracking
* 🔴 Overdue Task Highlighting
* 🔍 Live Search & Filters
* 📱 Fully Responsive Design
* 💾 MySQL Database Integration
* ⚡ Flash Messages & Real-Time Updates

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript
* Jinja2 Templates

## Backend

* Python
* Flask

## Database

* MySQL

---

# 📂 Project Structure

```text
study_planner/
│
├── app.py
├── config.py
├── database.sql
├── requirements.txt
├── README.md
│
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── login.html
│   ├── register.html
│   ├── subjects.html
│   ├── tasks.html
│   └── edit_task.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── models/
│   ├── user_model.py
│   ├── subject_model.py
│   └── task_model.py
│
└── utils/
    ├── auth.py
    └── database.py
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/study-planner-management-system.git
```

## 2️⃣ Open Project Folder

```bash
cd study-planner-management-system
```

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🗄️ Database Setup

## Create Database Using MySQL

Run this command:

```bash
mysql -u root -p < database.sql
```

Or:

* Open MySQL Workbench
* Create a new SQL tab
* Paste contents of `database.sql`
* Execute the script

---

# 🔧 Configure Database

Open:

```python
config.py
```

Update your MySQL credentials:

```python
DB_HOST = 'localhost'
DB_USER = 'root'
DB_PASSWORD = ''
DB_NAME = 'study_planner'
```

---

# ▶️ Run The Project

```bash
python app.py
```

---

# 🌐 Open In Browser

```text
http://127.0.0.1:5000
```

---

# 📸 Main Modules

## 🔐 Authentication

* User Registration
* User Login
* Password Hashing
* Session Management

## 📊 Dashboard

* Task Statistics
* Completion Progress
* Quick Overview

## 📖 Subject Management

* Add Subjects
* Delete Subjects
* Organize Study Materials

## ✅ Task Management

* Add Tasks
* Edit Tasks
* Delete Tasks
* Mark Tasks Complete
* Filter Tasks

---

# ✨ UI Highlights

* Modern Dashboard Design
* Clean Navigation Sidebar
* Responsive Layout
* Mobile-Friendly Interface
* Interactive Components
* Flash Notification System

---

# 🔒 Security Features

* Password Hashing using Werkzeug
* Session-Based Authentication
* Protected Routes
* Login Required Decorator

---

# 📦 Requirements

Install required packages:

```bash
pip install -r requirements.txt
```

Main dependencies include:

* Flask
* mysql-connector-python
* Werkzeug

---

# 🚀 Future Improvements

* 📅 Calendar Integration
* 🔔 Notification System
* 📈 Study Analytics
* 🌙 Dark Mode
* ☁️ Cloud Deployment
* 📱 Mobile App Version
* 📝 Notes Section

---

# 🧠 Learning Outcomes

This project demonstrates:

* Full-Stack Web Development
* Flask Routing
* MySQL Database Operations
* CRUD Functionality
* Authentication System
* Responsive UI Design
* MVC Project Structure

---

# 🏷️ GitHub Topics

```text
flask python mysql student-management study-planner task-manager fullstack-webapp responsive-design
```

---

# 👨‍💻 Author

GOBINDA CHANDRA PANDA

---

# 📜 License

This project is open-source and free to use for learning purposes.

---

# ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork the project
* 🛠️ Contribute improvements

---

# 📬 Contact

Feel free to connect for collaboration or feedback.
