# 🛍️ Vendrix

> **Browse. Cart. Checkout. Done.**

Vendrix is a full-featured E-Commerce Web Application built with **Java, JSP, Servlets, JDBC, and MySQL**, following a clean and scalable **MVC architecture**. From product browsing to secure checkout, Vendrix delivers a structured, real-world shopping experience backed by REST APIs, session-based authentication, and a powerful admin panel.

---

## 📌 Overview

Vendrix was designed to demonstrate end-to-end implementation of a real-world online shopping platform using core Java web technologies. It separates controllers, models, and views cleanly — making it an ideal portfolio and resume project showcasing strong **Java backend development** skills.

Whether you're exploring Java MVC architecture or looking for a reference implementation of a Servlet/JSP-based e-commerce app, Vendrix provides a solid, well-structured foundation.

---

## 🚀 Key Features

### 👤 User Features
- User registration & login with authentication
- Browse and search product catalog
- Add to cart, update cart items
- Place orders with full checkout flow
- Razorpay payment gateway integration
- Session management for secure access
- Responsive, mobile-friendly UI

### 🛠️ Admin Features
- Secure admin login
- Add, update, and delete products
- Manage product listings
- Full CRUD operations on application data

### ⚙️ System & Architecture
- Clean **MVC architecture** with separation of concerns
- **JDBC** for direct, efficient database connectivity
- **REST API** integration for structured data communication
- **MySQL** relational database
- Session tracking and validation
- Dynamic web pages using **JSP**
- Form validation and structured error handling
- Modular, scalable code structure

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Java** | Core backend language |
| **JSP** | Server-side dynamic HTML templating |
| **Servlets** | Request handling and routing |
| **JDBC** | Database connectivity |
| **MySQL** | Relational database for users, products, orders |
| **REST API** | Structured client-server communication |
| **HTML5 / CSS3** | Page structure and custom styling |
| **Bootstrap** | Responsive, mobile-first UI components |
| **JavaScript** | Client-side interactivity and validation |
| **Razorpay** | Payment gateway integration |
| **Apache Tomcat** | Web server / servlet container |

---

## 📂 Project Structure

```
Vendrix_java/
│
├── jp_application/
│   ├── src/main/java/
│   │   ├── controller/        # Servlet controllers (request handling)
│   │   ├── model/             # Entity classes & business logic
│   │   ├── dao/               # Data Access Objects (JDBC queries)
│   │   └── api/               # REST API endpoints
│   │
│   ├── src/main/webapp/
│   │   ├── jsp/               # JSP view pages
│   │   ├── css/               # Custom stylesheets
│   │   └── js/                # Client-side scripts
│   │
│   └── configuration files    # DB config, web.xml
│
├── database/
│   └── ecommerce.sql          # Database schema & seed data
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Dev-Mufaddal/Vendrix_java.git
cd Vendrix_java
```

### 2. Import Project into IDE

Open the project using any of the following:
- **IntelliJ IDEA**
- **Eclipse IDE**
- **NetBeans**

### 3. Configure the Database

Create the database in MySQL:

```sql
CREATE DATABASE ecommerce;
```

Import the schema from the provided SQL file:

```bash
mysql -u root -p ecommerce < database/ecommerce.sql
```

Update your database credentials in the configuration file:

```properties
db.url=jdbc:mysql://localhost:3306/ecommerce
db.username=root
db.password=yourpassword
```

### 4. Deploy & Run

Deploy the project on **Apache Tomcat Server** (v9+ recommended) from your IDE.

Visit the application in your browser:

```
http://localhost:8080/jp_application
```

---

## 🌐 Application Routes

| Route | Description | Access |
|---|---|---|
| `/` | Home / product listing | Public |
| `/register` | User registration | Public |
| `/login` | User login | Public |
| `/products` | Browse product catalog | Authenticated |
| `/search` | Search products | Authenticated |
| `/cart` | View and manage cart | Authenticated |
| `/checkout` | Checkout with Razorpay payment | Authenticated |
| `/orders` | View order history | Authenticated |
| `/logout` | End session | Authenticated |
| `/admin` | Admin control panel | Admin only |
| `/admin/products` | Manage products | Admin only |

---

## 🔒 Security Practices

- **Session Authentication** — Secure session tracking protects all authenticated routes
- **JDBC Prepared Statements** — Parameterized queries prevent SQL injection
- **Input Validation** — Both client-side (JS) and server-side (Java) validation
- **Separation of Concerns** — DAO, Model, and Controller layers are cleanly isolated
- **Admin Route Protection** — Admin pages inaccessible to regular users

---

## 🎯 Skills Demonstrated

This project demonstrates practical understanding of:

- Java web application development with JSP & Servlets
- MVC architecture design and implementation
- JDBC database connectivity and query handling
- REST API development and integration
- MySQL database integration with Java
- Session handling and authentication patterns
- Responsive frontend development with Bootstrap
- Payment gateway integration (Razorpay)
- Apache Tomcat server deployment
- GitHub version control workflow

---

## 📈 Roadmap & Future Improvements

- [ ] Migration to **Spring Boot** framework
- [ ] JWT-based API authentication
- [ ] Microservices architecture
- [ ] Cloud deployment (AWS / Azure)
- [ ] Docker containerization
- [ ] Product filtering and advanced search
- [ ] Advanced analytics dashboard for admin
- [ ] Email notifications for orders

---

## 👨‍💻 Author

**Mufaddal Kanchwala**
GitHub: [@Dev-Mufaddal](https://github.com/Dev-Mufaddal)
Email: mufaddalabbaskanchwala99@gmail.com

---

## 📜 License

This project is created for educational and portfolio purposes.

---

⭐ If you found this project useful or interesting, consider starring the repository!
