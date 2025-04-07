# 🏥 Hospital Management System – MySQL Database Schema

This project provides a complete SQL schema for a **Hospital Management System**, including tables for managing patients, doctors, appointments, prescriptions, billing, and inventory.

## 🧾 Overview

Designed for small to medium-sized hospital management, this database supports:
- Patient and doctor registration
- Appointment scheduling
- Prescription tracking
- Billing and payment records
- Inventory management

---

## 🛠️ Technologies Used

- MySQL / MariaDB
- SQL DDL (Data Definition Language)

---

## 📁 Included

- `HospitalManagementSystem.sql` – SQL file containing the full schema for database and table creation.

---

## 🗃️ Database Structure

### 🧑‍⚕️ Patients Table
Stores personal and contact information about patients.

### 👨‍⚕️ Doctors Table
Includes doctor profiles with specialties and contact info.

### 📅 Appointments Table
Tracks appointment details including status and reason for visit.

### 💊 Prescriptions Table
Stores medications and instructions linked to appointments.

### 🧾 Bills Table
Handles patient billing, status, and total charges.

### 💳 BillingDetails Table
Tracks payments made toward each bill.

### 📦 Inventory Table
Manages medical inventory and supplies, with reorder levels.

---

## ✅ Sample Features

- Relational design with foreign keys
- ENUM types for gender, status, and payment methods
- Timestamps for record creation
- Auto-incrementing primary keys for easy record tracking

---

## 📚 How to Use

1. Install a MySQL server (e.g., XAMPP, WAMP, MySQL Workbench).
2. Open your SQL client.
3. Run the `HospitalManagementSystem.sql` file to create the schema.
4. Start inserting data and running queries.

---

## 👨‍💻 Author

**Md Imran Hossain**  
SQL | Java | Python | Full-Stack Student Developer  
GitHub: [@RichrdxImran](https://github.com/RichrdxImran)

---

## 📜 License

This project is open-source and free to use for learning or educational purposes. Attribution appreciated.
