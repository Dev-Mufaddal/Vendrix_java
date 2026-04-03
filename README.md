# 🛒 E-Commerce Web Application using Java

## 📌 Overview

This project is a **full-featured E-Commerce Web Application** developed using **Java, JSP, Servlets, JDBC, MySQL, and REST APIs**, following the **MVC (Model-View-Controller)** architecture.

The application simulates a real-world online shopping platform where users can browse products, search items, manage cart functionality, and place orders securely. It also includes an admin panel for managing product data.

The project demonstrates strong understanding of **Java backend development**, **database integration**, **RESTful services**, and **responsive UI design**, making it suitable for **resume and portfolio presentation**.

---

## 🚀 Features

### 👤 User Features

* User Registration & Login Authentication
* Browse product catalog
* Search products
* Add to Cart functionality
* Update cart items
* Place orders
* Integrated payment flow (Razorpay - Dummy)
* Responsive UI using Bootstrap
* Session management for secure access

### 🛠️ Admin Features

* Admin login functionality
* Add new products
* Update product details
* Delete products
* Manage product listings
* Perform CRUD operations

### ⚙️ System Features

* MVC architecture implementation
* REST API integration
* JDBC database connectivity
* MySQL relational database
* Session tracking and validation
* Modular and scalable code structure
* Form validation and error handling
* Dynamic web pages using JSP
* Bootstrap-based responsive UI

---

## 🧑‍💻 Technologies Used

| Category             | Technology              |
| -------------------- | ----------------------- |
| Programming Language | Java                    |
| Backend              | JSP, Servlets, REST API |
| Database             | MySQL                   |
| Connectivity         | JDBC                    |
| Architecture         | MVC Pattern             |
| Frontend             | HTML, CSS, Bootstrap    |
| Payment Integration  | Razorpay (Dummy)        |
| Server               | Apache Tomcat           |
| Version Control      | Git, GitHub             |

---

## 📂 Project Structure

```id="l9q6tb"
ecom_with_java
│
├── jp_application
│   ├── src/main/java
│   │   ├── controller
│   │   ├── model
│   │   ├── dao
│   │   ├── api
│   │
│   ├── src/main/webapp
│   │   ├── jsp
│   │   ├── css
│   │   ├── js
│   │
│   └── configuration files
│
├── database
│   └── ecommerce.sql
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash id="gk5x1g"
git clone https://github.com/Dev-Mufaddal/ecom_with_java.git
```

### 2️⃣ Import Project into IDE

Open project using:

* IntelliJ IDEA
* Eclipse
* NetBeans

### 3️⃣ Configure Database

Create database:

```sql id="0ok7n7"
CREATE DATABASE ecommerce;
```

Import SQL file (if provided) OR create tables manually.

Update database configuration:

```properties id="5q55hs"
db.url=jdbc:mysql://localhost:3306/ecommerce
db.username=root
db.password=yourpassword
```

---

### 4️⃣ Run Application

Deploy project on **Apache Tomcat Server**

Access application in browser:

```id="2od7q9"
http://localhost:8080/jp_application
```

---

## 🎯 Skills Demonstrated

* Java Web Application Development
* MVC Architecture Implementation
* REST API Development & Integration
* JDBC Database Connectivity
* Authentication & Session Management
* CRUD Operations
* Payment Gateway Integration (Razorpay - Dummy)
* Responsive UI using Bootstrap
* Application Architecture & Code Structuring
* Git Version Control

---

## 💼 Resume Description

Developed a full-featured E-Commerce Web Application using Java, JSP, Servlets, JDBC, and MySQL following MVC architecture. Implemented user authentication, product search, cart management, admin CRUD operations, REST API integration, Bootstrap responsive UI, and dummy Razorpay payment gateway. Demonstrates strong backend development, database handling, and structured application design skills.

---

## 🔮 Possible Enhancement

* Migration to Spring Boot framework
* JWT-based authentication
* Microservices architecture
* Cloud deployment (AWS / Azure)
* Advanced analytics dashboard

---

## 📜 License

This project is created for educational and portfolio purposes.
