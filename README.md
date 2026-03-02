# 🎓 Student Management System

A simple Student Management System built using Flask and SQLite with user authentication and full CRUD operations.

---

## 🚀 Features

- 🔐 User Registration & Login
- ➕ Add Student
- 📋 View Students
- ✏ Edit Student
- ❌ Delete Student
- 🌐 API Endpoint → /api/students
- 💻 Modern Responsive UI

---

## 🛠 Tech Stack

- Python
- Flask
- SQLite
- HTML
- CSS

---

## ▶ How to Run

### 1️⃣ Create Virtual Environment

python -m venv venv

Activate it (Windows):

venv\Scripts\activate

---

### 2️⃣ Install Dependencies

pip install flask

OR (if using requirements.txt):

pip install -r requirements.txt

---

### 3️⃣ Run the Application

python app.py

---

### 4️⃣ Open in Browser

http://127.0.0.1:5000/

---

## 📁 Project Structure

Student-Management-System/
│
├── static/
│   └── style.css
│
├── templates/
│   ├── index.html
│   ├── view.html
│   ├── edit.html
│   ├── login.html
│   └── register.html
│
├── students.db
├── app.py
├── requirements.txt
└── .gitignore

---

## 🌍 Push Project to GitHub

1️⃣ Initialize Git

git init

2️⃣ Add Files

git add .

3️⃣ Commit

git commit -m "Initial commit"

4️⃣ Create Repository on GitHub  
Go to https://github.com  
Click New Repository  
Copy the repository URL  

5️⃣ Connect Local Project to GitHub

git remote add origin https://github.com/adapanavya2007-ai/student-management-system.git

6️⃣ Push to GitHub

git branch -M main  
git push -u origin main  

---

## 👩‍💻 Author

Adapa Navya

---

## ⭐ Future Improvements

- Role-based authentication (Admin/User)
- Search & Filter Students
- Pagination
- Deploy to cloud (Render / Railway)
