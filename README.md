# 🏥 Hospital Management System

A **Hospital Management System** developed using **Oracle SQL** to store, manage, and retrieve information related to patients, doctors, and nurses.

## 📌 Project Overview

The Hospital Management System is a database project designed to organize essential hospital information in a structured and efficient manner.

The system maintains records of **patients, doctors, and nurses** and establishes relationships between these entities. Each patient is assigned a unique ID, which can be used to identify and retrieve patient information easily.

The project demonstrates how a relational database can be used to manage hospital records, reduce manual data handling, and retrieve information efficiently using SQL queries.

## ✨ Features

* 👤 Patient record management
* 🆔 Unique ID for each patient
* 👨‍⚕️ Doctor information management
* 👩‍⚕️ Nurse information management
* 🔍 Search and retrieve patient details
* 🔎 Retrieve doctor and nurse information
* 🔗 Relationships between patients, doctors, and nurses
* 🗄️ Structured relational database
* ⚡ Efficient data retrieval using SQL queries

## 🛠️ Technologies Used

* **Database:** Oracle Database
* **Language:** SQL
* **Tool:** Oracle SQL Developer
* **Concepts:** Relational Database, Primary Keys, Foreign Keys, Constraints, SQL Queries

## 🗂️ Database Entities

The project consists of three main entities:

### 👤 Patient

Stores information about registered patients, including their unique patient ID and other relevant details.

### 👨‍⚕️ Doctor

Stores information about doctors and their details, including their association with patients.

### 👩‍⚕️ Nurse

Stores information about nurses and their relationship with patients.

## 🔗 Database Relationships

The database uses relationships between:

**Patient ↔ Doctor**

A patient can be associated with a doctor for their treatment or medical care.

**Patient ↔ Nurse**

A patient can be associated with a nurse responsible for their care.

Primary keys and foreign keys are used to maintain relationships and data integrity between the tables.

## 🔍 Example SQL Queries

```sql
-- Display all patients
SELECT * FROM PATIENT;

-- Display all doctors
SELECT * FROM DOCTOR;

-- Display all nurses
SELECT * FROM NURSE;

-- Search for a patient using Patient ID
SELECT *
FROM PATIENT
WHERE PATIENT_ID = 101;
```

## 🎯 Objectives

* To create a structured database for hospital records.
* To store patient, doctor, and nurse information efficiently.
* To establish relationships between hospital entities.
* To provide quick and easy access to stored information.
* To demonstrate practical implementation of Oracle SQL and relational database concepts.

## 📚 SQL Concepts Demonstrated

* CREATE TABLE
* INSERT
* SELECT
* UPDATE
* DELETE
* Primary Keys
* Foreign Keys
* Constraints
* JOIN Operations
* WHERE Conditions
* Data Retrieval and Filtering

## 🚀 Future Enhancements

The project can be extended in the future by adding:

* Doctor appointment management
* Room management
* Pharmacy management
* Billing system
* Laboratory reports
* Hospital staff management
* Web-based user interface
* User authentication and role-based access

## 👩‍💻 Author

**Pavithra V D**

This project was developed as a practical implementation of **Oracle SQL and relational database management concepts**.
