<div align="center">

# 🧺 <span style="font-size:34px; font-weight:800;">GOVLASH Laundry Management System</span>

<p style="font-size:15px; color:#555; max-width:700px;">
A JavaFX-based laundry management system with role-based access control, transaction tracking, and MySQL database integration.
</p>

<img src="assets/logo.png" width="160" alt="GOVLASH Logo" />

<br/><br/>

<img src="https://img.shields.io/badge/Java-JDK%2011+-orange" />
<img src="https://img.shields.io/badge/JavaFX-Desktop%20UI-blue" />
<img src="https://img.shields.io/badge/MySQL-8.0+-blue" />
<img src="https://img.shields.io/badge/Architecture-MVC-success" />

</div>

---

## ✨ Project Information

<p>
<strong>Application Type:</strong> Desktop Application<br/>
<strong>Architecture:</strong> Model-View-Controller (MVC)
</p>

### 👥 Team Members
<p>
Christopher Bryan Surya Handoko – 2702255691<br/>
Galih Ilham Nanwiprastama – 2702351374<br/>
Kevin Jesse Tiofan – 2702354590<br/>
Kevin Sealtiel Matthew Eddy – 2702255256
</p>

---

## 📖 1. Introduction

<p style="line-height:1.6;">
GOVLASH is a comprehensive laundry management system developed using <strong>JavaFX</strong> and <strong>MySQL</strong>.
The application is designed to streamline laundry service operations through structured workflows,
intuitive user interfaces, and role-based access control.
</p>

### 🌟 Key Features
<ul>
  <li>Multi-role system (Customer, Admin, Receptionist, Laundry Staff)</li>
  <li>Transaction management with real-time status tracking</li>
  <li>Dynamic service catalog and pricing</li>
  <li>Staff assignment and workflow automation</li>
  <li>Integrated notification system</li>
</ul>

---

## 🖼️ Application Preview

<div align="center">
  <img src="assets/login.png" width="600" />
  <br/>
  <em>Login & Registration Interface</em>
</div>

<br/>

<div align="center">
  <img src="assets/dashboard.png" width="600" />
  <br/>
  <em>Role-Based Dashboard View</em>
</div>

---

## 🛠️ 2. Technology Stack

<p><strong>Frontend:</strong> JavaFX for building responsive desktop user interfaces.</p>
<p><strong>Programming Language:</strong> Java (JDK 11+) ensuring object-oriented and cross-platform development.</p>
<p><strong>Database:</strong> MySQL 8.0+ for structured and reliable data storage.</p>
<p><strong>Connectivity:</strong> MySQL Connector/J (JDBC) for database communication.</p>
<p><strong>Architecture:</strong> Model-View-Controller (MVC) for separation of concerns.</p>

---

## 🧩 3. System Architecture

<div align="center">
  <img src="assets/mvc-diagram.png" width="650" />
  <br/>
  <em>Model-View-Controller Architecture</em>
</div>

<p style="line-height:1.6;">
The MVC architecture separates the system into Model, View, and Controller layers,
improving maintainability, scalability, and code organization.
</p>

---

## 🗄️ 4. Database Schema

<div align="center">
  <img src="assets/erd.png" width="650" />
  <br/>
  <em>Entity Relationship Diagram (ERD)</em>
</div>

<p style="line-height:1.6;">
The database schema supports user authentication, service management,
transaction processing, and role-based workflows.
</p>

---

## ⚙️ 5. Installation Guide

### Prerequisites
<ul>
  <li>JDK 11 or higher</li>
  <li>MySQL Server 8.0+</li>
  <li>JavaFX SDK</li>
  <li>MySQL Connector/J</li>
</ul>

### Setup Steps
<ol>
  <li>Start XAMPP and enable MySQL</li>
  <li>Create database <code>govlash_database</code> using phpMyAdmin</li>
  <li>Import the provided SQL scripts</li>
  <li>Configure JavaFX and JDBC in your IDE</li>
  <li>Run <code>Main.java</code></li>
</ol>

---

## 📁 Project Structure

```text
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
