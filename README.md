🧺 GOVLASH Laundry Management System

A JavaFX-based laundry management application with role-based access control and MySQL integration.

📌 Project Information

Application Name: GOVLASH Laundry System
Type: Desktop Application
Architecture: Model-View-Controller (MVC)

👥 Team Members

Christopher Bryan Surya Handoko – 2702255691

Galih Ilham Nanwiprastama – 2702351374

Kevin Jesse Tiofan – 2702354590

Kevin Sealtiel Matthew Eddy – 2702255256

📖 1. Introduction
🖼️ Application Preview

(Screenshots of the GOVLASH Laundry System interface)

1.1 Overview

GOVLASH is a comprehensive laundry management system developed using JavaFX and MySQL. The application is designed to streamline laundry service operations through an intuitive user interface, structured workflows, and role-based access control for different user types.

1.2 Key Features

Multi-role system (Customer, Admin, Receptionist, Laundry Staff)

Transaction management with real-time status tracking

Service catalog with dynamic pricing

Staff assignment and workflow automation

Notification system for transaction updates

🛠️ 2. Technology Stack

The GOVLASH system is built using stable and industry-relevant technologies suitable for desktop-based enterprise applications.

Component	Technology
Frontend	JavaFX
Language	Java (JDK 11+)
Database	MySQL 8.0+ (XAMPP)
Database Driver	MySQL Connector/J
Architecture	MVC (Model-View-Controller)
🧩 3. System Architecture
3.1 MVC Pattern
Model Layer

UserModel – User authentication and role management

ServiceModel – Laundry service catalog operations

TransactionModel – Transaction lifecycle handling

NotificationModel – System notifications

View Layer

LoginView & RegisterView – User authentication interfaces

CustomerView – Customer dashboard and order management

AdminView – Service and employee management

ReceptionistView – Transaction processing interface

StaffView – Laundry staff task dashboard

Controller Layer

Controllers act as intermediaries between Models and Views, handling business logic, validation, and role-based workflows. Each user role is supported by a dedicated controller.

3.2 Database Connection

Database Name: govlash_database

Host: localhost:3306

Username: root

Password: (empty – default XAMPP setup)

🗄️ 4. Database Schema
4.1 Users Table
Column Name	Type	Description
UserID	INT, PK, AI	Primary Key
UserName	VARCHAR(50)	Unique username
UserEmail	VARCHAR(100)	User email
UserPassword	VARCHAR(255)	Encrypted password
UserGender	VARCHAR(10)	Male / Female
UserDOB	VARCHAR(20)	Date of birth
UserRole	VARCHAR(50)	Customer / Admin / Receptionist / Laundry Staff
⚙️ 5. Installation Guide
5.1 Prerequisites

JDK 11 or higher

MySQL Server 8.0+

JavaFX SDK

MySQL Connector/J

5.2 Database Setup

Start XAMPP and enable MySQL

Open phpMyAdmin

Create a database named govlash_database

Execute the provided SQL scripts

5.3 Application Setup

Extract the project files

Import the project into your IDE (IntelliJ / NetBeans / Eclipse)

Add JavaFX SDK and MySQL Connector/J to project libraries

Run Main.java

👤 6. User Roles & Features
6.1 Customer

Create new laundry transactions

View transaction history

Receive real-time notifications

6.2 Admin

Manage laundry services

Manage employee data

Monitor all transactions

6.3 Receptionist

View pending transactions

Assign laundry staff

Update transaction status

6.4 Laundry Staff

View assigned tasks

Mark laundry as completed

🚀 7. Usage Guide
7.1 Customer

Register an account

Log in

Place a laundry order

7.2 Admin

Manage services, staff, and monitor reports

7.3 Receptionist

Assign transactions and manage workflow

7.4 Laundry Staff

Complete assigned laundry tasks

📁 Project Structure
GOVLASH/
├── src/
│   ├── controller/
│   ├── model/
│   ├── view/
│   └── Main.java
├── assets/
│   ├── logo.png
│   ├── login.png
│   ├── dashboard.png
│   ├── mvc-diagram.png
│   └── erd.png
├── README.md
└── govlash_database.sql
📄 License

This project is developed for academic purposes.

📬 Contact

For questions or further development, please contact the project contributors.
