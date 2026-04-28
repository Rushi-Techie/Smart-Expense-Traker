# Smart-Expense-Traker
# 💰 Full Stack Expense Tracker (JavaFX + Spring Boot + SQL)

## 📌 Project Overview

This is a **Full Stack Expense Tracker Application** built using:

* **Frontend:** JavaFX (Desktop UI)
* **Backend:** Spring Boot (REST APIs)
* **Database:** MySQL

The application allows users to:

* Add, update, and delete expenses
* Track spending
* View expense history

---

## 🛠️ Tech Stack

* Java (JDK 17)
* Spring Boot
* JavaFX
* MySQL
* Maven

---

## ⚙️ Prerequisites

Make sure you have installed:

* Java JDK 17+,21,25
* Maven
* MySQL

Check installation:

```bash
java -version
mvn -version
```

---

## 🗄️ Database Setup

1. Open MySQL and create database:

```sql
CREATE DATABASE expense_tracker;
```

2. Update database configuration in:

```
backend/src/main/resources/application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/expense_tracker
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

---

## 🚀 How to Run the Project

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

---

### 🔹 Step 2: Run Backend (Spring Boot)

```bash
cd backend
mvn spring-boot:run
```

Backend will run on:

```
http://localhost:8080
```

---

### 🔹 Step 3: Run Frontend (JavaFX)

```bash
cd frontend
mvn clean javafx:run
```

This will launch the desktop application.

---

## 📂 Project Structure

```
project-root/
│
├── backend/        # Spring Boot APIs
├── frontend/       # JavaFX UI
└── README.md
```

## 📈 Future Enhancements

* User authentication
* Expense categories
* Charts & analytics
* Cloud deployment

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📄 License

This project is open-source and free to use.

---

## 👨‍💻 Author

**Rushikesh Sonawane**

---
