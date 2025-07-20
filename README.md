# 🏡 PG Hunt — PG Hunting Web App

Welcome to **PG Hunt**, your one-stop solution for finding the perfect PG accommodation. This full-stack web application is built to simplify and streamline the student housing experience with powerful features like filtering, sorting, authentication, and more.

---

## 🔍 What is PG Hunt?

PG Hunt is a PG-hunting website designed to help students and professionals find suitable paying guest accommodations across different states. Whether you're looking for budget-friendly rooms, gender-specific housing, or high-safety options, PG Hunt has got you covered.

---

## ✨ Key Features

- 🔍 **Search & Browse PGs** by:
  - ✅ State
  - ✅ Gender (Boys/Girls)
  - ✅ Rent (Low to High & High to Low)
  - ✅ Safety Score

- 🏘️ **PG Detail Pages** with:
  - Photos  
  - Amenities  
  - Monthly Rent  
  - Safety ratings  
  - Contact information  
  - Resident testimonials  

- ❤️ **Mark PGs as Interested** (like/favorite toggle)

- 👤 **Authentication**:
  - Signup/Login for users
  - Session-based access control

- 🧾 **Testimonials & Reviews**

---

## ⚙️ How it Works

1. **Frontend**:
   - Built using HTML, CSS, JavaScript  
   - Responsive and user-friendly design

2. **Backend**:
   - Developed in PHP  
   - Interacts with MySQL database to store and retrieve PG data

3. **Database**:
   - MySQL DB (structure and dummy data available)  
   - Stores user details, PG listings, amenities, and testimonials

4. **Session Handling**:
   - PHP sessions used to manage login/logout and user state

---

## 🚀 Getting Started

### ✅ Prerequisites

- PHP installed (or use XAMPP for local server)  
- MySQL server or phpMyAdmin  
- VS Code or any code editor  

### 🛠️ Installation

1. **Clone the Repository**

```
git clone https://github.com/geeta614/pg-hunt-php.git
cd pg-hunt-php
```

2. **Import the Database**

- Open phpMyAdmin
- Create a new database: pglife
- Import the provided SQL dump file (available in the repo)

3. **Run the Project**

```
php -S localhost:8000
```

Open your browser and visit:
http://localhost:8000
