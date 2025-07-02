
# 🏆 Sports Club Management System (SCMS)

The **Sports Club Management System (SCMS)** is a Java-based, object-oriented desktop application designed to streamline the operations of sports clubs. It enables efficient management of teams, players, tournaments, schedules, and results through a scalable and user-friendly system with database integration.

---

## 📄 Abstract

The SCMS provides an intuitive GUI for club administrators, coaches, and members to manage key aspects of club operations. Built using **Java (Swing/JavaFX)** and **MS Access** via **JDBC**, the system modularizes entities like teams, tournaments, departments, and results. It focuses on **CRUD operations**, **scheduling conflict resolution**, **secure access**, and **performance analytics**.

---

## 📌 Table of Contents

* [Abstract](#-abstract)
* [Introduction](#-introduction)
* [Project Scope](#-project-scope)
* [Objectives](#-objectives)
* [Methodology](#-methodology)
* [Implementation](#-implementation)
* [OOP Principles & UML Overview](#-oop-principles--uml-overview)
* [Technologies Used](#-technologies-used)
* [Features](#-features)
* [How to Run](#-how-to-run)
* [Future Enhancements](#-future-enhancements)
* [Conclusion](#-conclusion)

---

## 🚀 Introduction

SCMS replaces outdated, manual sports club workflows with a modern system that improves **efficiency**, **data integrity**, and **user experience**. It integrates Java GUI, relational databases, and reporting tools to support administrative functions such as:

* Team and member management
* Tournament organization
* Schedule planning and conflict resolution
* Secure access and data tracking

---

## 🧭 Project Scope

The SCMS project covers:

* 🧑‍🤝‍🧑 **Team Management** – Manage team info, departments, and coaches
* 🧍 **Member Management** – Maintain member profiles and roles
* 🏛️ **Department Structuring** – Organize departments for role clarity
* 🏅 **Tournament Oversight** – Add, edit, and manage tournaments
* 📆 **Schedule Handling** – Plan and track event schedules
* 📊 **Result Management** – Record and analyze match results
* 🔐 **User Authentication** – Protect admin functions with secure login

The system is designed to be **scalable, modular**, and **customizable** for sports clubs of all sizes.

---

## 🎯 Objectives

* ✔️ Implement easy-to-use CRUD interfaces
* ✔️ Ensure data consistency and integrity
* ✔️ Handle scheduling conflicts efficiently
* ✔️ Generate insightful performance reports
* ✔️ Support secure login with authorization
* ✔️ Enhance usability and maintainability

---

## 🧪 Methodology

* **Language:** Java
* **Front-end:** Java Swing / JavaFX GUI
* **Back-end:** MS Access via JDBC
* **Database Connection:** ODBC Driver
* **Tools:** Visual Studio Code / NetBeans

### Key Libraries and Tools

* `JDBC`: Java database connectivity for SQL operations
* `MS Access ODBC Driver`: Bridges Java to Access DB
* `SQL`: Used for querying and managing data

---

## 🧱 Implementation

### 📋 Requirements Gathering

* Input from admins, coaches, and members
* Features based on tournament needs, schedule management, and data access

### 🏗️ System Design

* Modular architecture: Team, Schedule, Tournament, Results modules
* User-friendly interface using Swing or JavaFX
* Data stored in MS Access, accessed using JDBC

### 🧑‍💻 Development

* Java classes for each entity (Team, Tournament, etc.)
* Encapsulation of methods like `addData()`, `updateData()`, `deleteData()`
* Validation for input and constraints

### 🔍 Testing & Deployment

* Unit and integration testing
* User acceptance testing
* Training resources and future maintenance plans

---

## 💡 OOP Principles & UML Overview

* **Encapsulation:** Each class contains relevant attributes and methods
* **Constructors:** Initialize object states during creation
* **Access Modifiers:** `private` for attributes, `public` for getters/setters
* **Class Diagram Includes:**

  * `Results`, `Schedule`, `Team`, `Tournament`
  * Methods like `addData()`, `getData()`, `deleteData()`
* **Associations:** UML depicts relationships between modules
* **Polymorphism & Inheritance:** Prepared for extensions and shared behavior

---

## 🧰 Technologies Used

| Feature       | Technology         |
| ------------- | ------------------ |
| Language      | Java               |
| GUI Framework | Swing / JavaFX     |
| Database      | MS Access          |
| Database API  | JDBC               |
| SQL Queries   | CRUD operations    |
| IDE           | NetBeans / VS Code |

---

## 🌟 Features

* 🔧 CRUD Operations for teams, players, and tournaments
* 📆 Conflict-checked schedule planning
* 📊 Performance and result reports
* 🔐 Secure login and user access
* 🧾 Dynamic GUI forms and validation
* 🔁 Update/delete operations for all modules
* 💾 Persistent storage using MS Access

---

## ▶️ How to Run

1. Clone the repository or download the ZIP
2. Open the project in **NetBeans** or your preferred IDE
3. Set up MS Access Database and DSN via ODBC
4. Run the application `Main.java`
5. Use GUI to manage data (teams, players, schedules, etc.)

> Ensure JDBC driver and MS Access ODBC driver are configured.

---

## 🔧 Future Enhancements

* Migrate to MySQL or PostgreSQL for larger clubs
* Add role-based dashboards (Admin/Coach/Member)
* Enable real-time notifications for match updates
* Integrate PDF report exports for tournaments
* Add web version with Spring Boot backend

---

## 📚 Conclusion

The **Sports Club Management System** is a reliable, scalable, and comprehensive tool that improves the way sports clubs are managed. With intuitive interfaces, modular design, and strong database interaction, it meets modern sports organizations’ needs and sets a foundation for future growth.


![image](https://github.com/user-attachments/assets/56f8f28b-69f5-477f-b9dd-bf514e228e65)

![image](https://github.com/user-attachments/assets/12fd337d-332d-4796-ba69-4ffde87aafa9)

![image](https://github.com/user-attachments/assets/94c21a78-3da3-4928-bef3-16e94ff5c902)

![image](https://github.com/user-attachments/assets/4073891d-61cd-4e6b-808d-ed9a6cfdb94a)

![image](https://github.com/user-attachments/assets/11c3bc30-1500-4244-8730-b5cd822d285f)


![image](https://github.com/user-attachments/assets/a87d4fd3-18b7-446a-8c0d-3b24c2e92489)


![image](https://github.com/user-attachments/assets/05592f2a-7207-4724-b2dd-abba109a3ddd)


![image](https://github.com/user-attachments/assets/504f9fa3-3318-470e-9d4f-ad384b624b87)


![image](https://github.com/user-attachments/assets/be4fa7d0-3fd5-44ae-aed1-5ba14f9393c2)


![image](https://github.com/user-attachments/assets/1d60694f-9b63-46cf-912d-6c2f7f3179e1)


![image](https://github.com/user-attachments/assets/9313bcc5-fe9a-4641-aab5-ebde9fcb04c1)


![image](https://github.com/user-attachments/assets/5f61c934-369d-4efa-99b6-d62197a6a599)

![image](https://github.com/user-attachments/assets/820ef1c1-5b13-4277-80da-755957c7cf0a)


![image](https://github.com/user-attachments/assets/7657e389-7eac-42d6-8e47-4f3fa5550003)

![image](https://github.com/user-attachments/assets/3764d0d6-642b-4e20-83d1-8f2dedc03d61)


![image](https://github.com/user-attachments/assets/a58e14f2-a7a1-47cd-8efa-817e345f0ea5)

![image](https://github.com/user-attachments/assets/dfe54b6a-b2f6-470a-a122-460a7fa9adfe)







