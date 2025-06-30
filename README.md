# 🎓 Student Information System

A web-based student information system built using **ASP.NET Web Forms** and **Supabase (PostgreSQL)**. This platform enables efficient student and course management, assignment tracking, grading, and includes a built-in marketplace for students and admins.

---

## 🔧 Tech Stack

- **Frontend & Backend:** ASP.NET Web Forms  
- **Database:** Supabase (PostgreSQL)  
- **Authentication:** Role-based access with Bcrypt password hashing  
- **Charts:** Chart.js  
- **IDE:** Visual Studio  

---

## 👥 User Roles

### Admin
- Manage student records (CRUD)
- Create, update, and delete courses
- Enroll students into courses
- Create and grade assignments
- Manage all marketplace listings

### Student
- Self-enroll into available courses
- View and submit assignments
- View grades and GPA
- Create marketplace listings

---

## 📚 Key Features

### ✅ Student Management
- Add, edit, and delete student records  
- Manage first name, last name, email, enrollment date, and admin status  

### 📘 Course Management
- Create, edit, and delete courses  
- Assign students to specific courses  

### 🎓 Course Enrollment
- Admins can manually enroll students  
- Students can self-enroll in available courses  

### 📝 Assignment & Grading
- Admins create assignments with title, description, and due date  
- Grading scale: **1.0 – 6.0** (Swiss system)  
- GPA is automatically calculated and displayed on student dashboards  

### 📊 Data Visualization
- Grade distribution across all courses  
- Student count per course  
- Implemented using Chart.js  

### 🔐 User Authentication
- Role-based access (Admins vs. Students)  
- Passwords hashed using Bcrypt  

### 🛒 Marketplace
- Users can post listings in:
  - Books
  - Housing
  - Tutoring
- Listings include title, description, price, and contact email  
- Admins can manage all listings  
- Users can bookmark listings  

---

## 🖼️ UI/UX Design

- Clean and intuitive interface  
- Responsive layout with consistent styling  
- Interactive charts and easy navigation  
- Optimized for desktop and mobile devices

---

## 🚀 Getting Started

1. **Clone the repository**
2. **Open the solution in Visual Studio**
3. **Configure Supabase connection**
4. **Update the connection string in Web.config**
5. **Run the application**

---

## 📄 License

This project is intended for academic use only and is not licensed for commercial use

---

## 🙋‍♂️ Author

Developed as part of a university course project.
